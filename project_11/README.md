## Описание проекта "Построение модели определения стоимости автомобиля"
Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторические данные необходимо построить модель для определения стоимости автомобиля.

### Задачи
Разработка системы рекомендации стоимости автомобиля на основе его описания.

### Данные
**Признаки**

- DateCrawled — дата скачивания анкеты из базы
- vehicle_type — тип автомобильного кузова
- registration_year — год регистрации автомобиля
- gearbox — тип коробки передач
- Power — мощность (л. с.)
- model — модель автомобиля
- Kilometer — пробег (км)
- RegistrationMonth — месяц регистрации автомобиля
- fuel_type — тип топлива
- Brand — марка автомобиля
- not_repaired — была машина в ремонте или нет
- DateCreated — дата создания анкеты
- NumberOfPictures — количество фотографий автомобиля
- PostalCode — почтовый индекс владельца анкеты (пользователя)
- LastSeen — дата последней активности пользователя

**Целевой признак**

- Price — цена (евро)

### Используемые библиотеки
Python, Pandas, lightgbm