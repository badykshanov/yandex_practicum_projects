# Определение возраста покупателей

## Данные

Папка с фотографиями ChaLearn Looking at People: (224, 224, 3) (цветные)

- file_name — имя фотограции

Целевой признак:

- real_age — настоящий возраст человека на фотограции

# Задача


Необходимо построить нейросетью для определения возраста человека на фотограции.
Решение производится библиотеками tensorflow.keras с применением архитектуры ResNet50.

Метрика качества модели: MAE.


# Используемые библиотеки

- pandas
- numpy
- os
- tensorflow
- matplotlib
- PIL