# Восстановление золота из руды

## Данные

Данные находятся в трёх файлах:

- gold_recovery_train_new.csv — обучающая выборка
- gold_recovery_test_new.csv — тестовая выборка
- gold_recovery_full_new.csv — исходные данные

В выборках различные параметры сырья на разных этапах обработки, имеющие вид [этап].[тип_параметра].[название_параметра]. Пример: rougher.input.feed_ag

# Задача

Нужно спрогнозировать сразу две величины:
1.	эффективность обогащения чернового концентрата rougher.output.recovery;
2.	эффективность обогащения финального концентрата final.output.recovery.

Метрика качества модели:

Итоговое sMAPE = 25% sMAPE(rougher) + 75% sMAPE(final)

 sMAPE (англ. Symmetric Mean Absolute Percentage Error, «симметричное среднее абсолютное процентное отклонение»

# Используемые библиотеки

- pandas
- os
- seaborn
- matplotlib
- numpy
- pylab
- sklearn