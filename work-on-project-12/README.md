# Классификация токсичных комментариев

## Данные

- text — текст комментария на английском языке

# Задача

Целевой признак:

- toxic — является ли текст токсичным в формате int

Необходимо построить модель для классификации комментариев. 
Два варианта решения в разных файлах: с переводом в векторные выражения мешок слов, N-граммы, TF-IDF, и c использованием BERT.


Метрика качества модели: F1.

# Используемые библиотеки

- pandas
- numpy
- os
- re
- nltk
- string
- lightgbm
- sklearn
- tqdm
- joblib