 # Название проекта
 **Обучение модели классификации комментариев**
 ## Цель
Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Необходимо обучить модель классификации комментариев.
 # План работы
- Подготовить и обработать данные
- Лемматизировать текст и очистить от лишних символов
- Токенизировать текст
- Проверить баланс классов в целевом признаке
- Разбить данные на выборки (тренировочную и тестовую)
- Выделить в выборках признаки и целевой признак
- Обучить модели (LinearRegression, CatBoostRegressor, RandomForestClassifier)
- Проверить лучшую модель на тестовой выборке
- Значеие метрики F1 должно быть меньше 0.75
- Сдеалть вывод с рекомендацией наилучшей модели заказчику.
# Вывод 
По итогам качества обучения выбрали модель LogisticRegression , рекомендуем данную модель для классификации комментариев в новом сервисе интернет-магазина.

# Используемые инструменты
BERT,Pandas,Python,nltk,tf-idf, NLP, Машинное обучение
# Статус проекта
Завершен
