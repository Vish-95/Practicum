## Описание проекта "Обучение модели классификации комментариев"
Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

## Задача
обработка естественного языка, NLP

## Данные
- *text* – текст комментария,
- *toxic* — целевой признак

## Используемые библиотеки
Python, Pandas, BERT, nltk, tf-idf