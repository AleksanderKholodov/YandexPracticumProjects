# Определение токсичности комментариев

[ipynb](https://github.com/AleksanderKholodov/YandexPracticumProjects/tree/main/14_toxic_comments_classification/14_toxic_comments_classification.ipynb)

## Описание проекта

Построение модели машинного обучения для классификации комментариев к описанию товаров интернет-магазина на токсичные и не токсичные


## Навыки и инструменты

- **python**
- **pandas**
- **nltk**
- **tf-idf**
- **spacy**
- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.linear_model.**LogisticRegression**
- sklearn.tree.**DecisionTreeClassifier**
- sklearn.linear_model.**SGDClassifier**
- sklearn.model_selection.**RandomizedSearchCV**
- sklearn.model_selection.**train_test_split**
- sklearn.pipeline.**Pipeline**

## Общий вывод

Проведено исследование данных на дисбаланс классов. Данные очищены и лемматизированы.
Проведена векторизация и обучение нескольких моделей с подбором гиперпараметров в пайплайне.

Выбрана и протестирована лучшая модель.
