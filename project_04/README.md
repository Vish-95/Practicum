## Описание проекта "Определение выгодного тарифа для телеком компании"
Проведен предварительный анализ использования тарифов на выборке клиентов,
проанализировано поведение клиентов при использовании услуг оператора и
рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка
данных, их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и
различии выручки абонентов из Москвы и других регионов.

### Данные 

**Данные о звонках**
- id — уникальный номер звонка
- call_date — дата звонка
- duration — длительность звонка в минутах
- user_id — идентификатор пользователя, сделавшего звонок

**Данные об интернет-сессиях**
- id — уникальный номер сессии
- mb_used — объём потраченного за сессию интернет-трафика (в мегабайтах)
- session_date — дата интернет-сессии
- user_id — идентификатор пользователя

**Данные о сообщениях**
- id — уникальный номер сообщения
- message_date — дата сообщения
- user_id — идентификатор пользователя, отправившего сообщение

**Данные о тарифе**
- messages_included	 – включено количество смс
- mb_per_month_included – включено количесвто мб
- minutes_included – включено минут разговора
- rub_monthly_fee – ежемесячная плата
- rub_per_gb – стоимость 1 гб интернета
- rub_per_message – стоимость 1 смс
- rub_per_minute – стоимость 1 минуты разговора
- tariff_name – название тарифа

**Данные о пользователях**
- user_id –уникальный идентификатор пользователя
- age – возраст пользователя
- churn_date – дата прекращения пользования тарифом (если значение пропущено, то тариф ещё действоал на момент выгрузки данных)
- city – город проживания пользователя
- first_name – имя пользователя
- last_name – фамилия пользователя
- reg_date – дата подключения тарифа (день, месяц, год)
- tariff – название тарифного плана
### Задачи
На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и поиск оптимального тарифа

### Используемые библиотеки
Python, Pandas, Matplotlib, NumPy, SciPy
