 # Название проекта
 **Построение модели определения стоимости автомобиля**
 ## Цель
Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторические данные необходимо построить модель для определения стоимости автомобиля.
 # План работы
- Подготовить данные;
- Подготовить выборки для обучения моделей;
- Построить и обучить несколько моделей;
- Проанализировать время обучения, время предсказания и качество моделей;
- Проверить качество лучшей модели на тестовой выборке.

 # Вывод 
 
Мы использовали для обучения модели CatBoostRegressor, LightGBM, LinearRegression, RandomForestRegressor.

По итогам качества и скорости обучения побеждает модель ***CatBoostRegressor***, рекомендуем данную модель для определения рыночной стоимости авотмобиля.

# Используемые инструменты

Python
Pandas
lightgbm

# Статус проекта
Завершен



```python

```
