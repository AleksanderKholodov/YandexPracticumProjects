# Прогнозирование температуры стали во время плавки

[ipynb](https://github.com/AleksanderKholodov/YandexPracticumProjects/blob/main/14.toxic_comments/14.toxic_comments.ipynb)

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

Был проведен исслдеовательский анализ данных, предобработаны данные, сегнерированы новые признаки, обучено несколько моделей.
По результатам тестирования выбрана одна для запуска в производство.
