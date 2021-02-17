# Предсказание оттока клиентов банка

По историческим данным о поведении клиентов бнка был спрогнозирован отток.
Источник данных: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

### Библиотеки:
- pandas
- numpy
- sklearn
- matplotlib

Были проведены различные методы устранения дисбаланса классов.
Лучшие метрики качества на тестовой выборки показал модель **RandomForestClassifier** (F1 = 0.596, AUC-ROC = 0.8507)
