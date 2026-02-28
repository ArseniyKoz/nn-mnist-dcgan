# DCGAN на MNIST

Pet-проект по сверточному GAN (DCGAN) для генерации изображений рукописных цифр.

## Что сделано

- Сверточные блоки Generator/Discriminator.
- Нормализация и подготовка входного пространства шума.
- Отслеживание прогресса генерации по эпохам.

## Стек

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Jupyter Notebook

## Как запустить

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook nn_mnist_dcgan.ipynb
```

## Результаты

Реализована DCGAN-конфигурация с улучшением визуального качества относительно базового GAN.

## Чему научился

- Проектировать архитектуру генератора для повышения детализации.
- Подбирать learning rate/betas для стабильного обучения.

## Ограничения и что улучшить

- Добавить регуляризацию и автоматическое сохранение лучших чекпойнтов.

## Автор

Арсений Козлов - [github.com/ArseniyKoz](https://github.com/ArseniyKoz)


