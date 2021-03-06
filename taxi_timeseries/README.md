# Прогноз количества заказов такси на час
В таблице содержатся исторические данные о заказах такси в аэропортах. Необходимо спрогнозировать количество заказов такси на следующий час, 
чтобы привлекать больше водителей в период пиковой нагрузки.

## Библиотеки:
- pandas
- numpy
- seaborn
- matplotlib
- statsmodels
- sklearn
- lightgbm

Был проведён предварительный анализ временного ряда на наличие тренда и сезонности. На основании выводов были сгенерированы новые признаки, на которых обучалась модель.


![timeseries plot](timeseries_img.png)
### Вывод:

- Наименьшее значение RMSE показывает модель `RandomForestRegressor` со значением **43.5918**
- По графику видно, что минимумы `RandomForestRegressor` предсказывает неплхо, а вот максимумы так же плохо как и другие модели. 
Предсказать потенциальный недостаток машин в районе аэропорта будет сложно. Необходимо искать более подходящую модель.
