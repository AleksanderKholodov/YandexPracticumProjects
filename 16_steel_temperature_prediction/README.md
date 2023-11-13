# Прогнозирование температуры стали во время плавки

[ipynb](https://github.com/AleksanderKholodov/YandexPracticumProjects/tree/main/16_steel_temperature_prediction/16_steel_temperature_prediction.ipynb)

## Описание проекта

Построение модели машинного обучения для предсказания температуры стали во время плавки, которая будет использована для уменьшения потребления электроэнергии на металлургическом комбинате.


## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **seaborn**

- sklearn.linear_model.**LinearRegression (Ridge, Lasso, ElasticNet)**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.tree.**DecisionTreeRegressor**
- sklearn.pipeline.**Pipeline**
- sklearn.model_selection.**train_test_split**
- sklearn.metrics.**mean_absolute_error**
- sklearn.model_selection.**GridSearchCV (RandomizedSearchCV)**
- catboost.**CatBoostRegressor**
- **matplotlib**

## Общий вывод

Был проведен исследовательский анализ данных, предобработаны данные, сегнерированы новые признаки, обучено несколько моделей.
По результатам тестирования выбрана одна для запуска в производство.
