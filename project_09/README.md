## Описание проекта "Исследование технологического процесса очистки золота"
Строится модель машинного обучения для промышленной компании, разрабатывающая решения для эффективной работы промышленных предприятий. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды на основе данных с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

### Задача
Спрогнозировать концентрацию золота при проведении процесса очистки золота.

### Данные
**Технологический процесс**

- `Rougher feed` — исходное сырье

- `Rougher additions (или reagent additions)` — флотационные реагенты: 
Xanthate, Sulphate, Depressant

- `Xanthate **` — ксантогенат (промотер, или активатор флотации);

- `Sulphate` — сульфат (на данном производстве сульфид натрия);

- `Depressant` — депрессант (силикат натрия).

- `Rougher process` (англ. «грубый процесс») — флотация

- `Rougher tails` — отвальные хвосты

- `Float banks` — флотационная установка

- `Cleaner process` — очистка

- `Rougher Au` — черновой концентрат золота

- `Final Au` — финальный концентрат золота

**Параметры этапов**

- `air amount` — объём воздуха

- `fluid levels` — уровень жидкости

- `feed size` — размер гранул сырья

- `feed rate` — скорость подачи

**Этапы**

- `rougher` — флотация

- `primary_cleaner` — первичная очистка

- `secondary_cleaner` — вторичная очистка

- `final` — финальные характеристики

**тип_параметра**

- `input` — параметры сырья

- `output` — параметры продукта

- `state` — параметры, характеризующие текущее состояние этапа

- `calculation` — расчётные характеристики

### Используемые библиотеки
Python, Pandas, Matplotlib, NumPy, Scikit-learn