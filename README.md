# Предсказание цены автомобиля


Многие знают про маркетплейсы где продаются б/у вещи, на которых есть возможность недорого купить качественную и полезную вещь. Но всегда волнует вопрос - кто и как устанавливает цену, и какие его характеристики больше всего влияют на итоговую стоимость продажи?! Вопрос становиться особо актуальным, если речь идет про дорогие товары, например про автомобили!    

В рамках данного исследования будет вестить работа с данными о продажах автомобилей на вторичном рынке. 

**Целью проекта будет *разработанная модель* предсказания стоимости автомобиля на вторичном рынке.**


## Данные
**train.csv** - информация о продажах (~440000) автомобилей с аукционов, которые будут использоваться в качестве обучающих данных.

**test.csv** - информация о продажах (~110000) автомобилей с аукционов, которые будут использоваться в качестве тестовых данных. Ваша задача - предсказать значение 'sellingprice' для каждого автомобиля из этого датасета.

**sample_submission.csv** - файл предсказаний в правильном формате.
vin - идентификатор каждого автомобиля в тестовом наборе.
sellingprice - Целевой признак. Для каждого автомобиля предскажите числовое значение стоимости автомобиля.


## Описание полей данных
`year` - год производства

`make` - производитель

`model` - модель

`trim` - модификация

`body` - тип кузова

`transmission` - тип КПП

`vin` - идентификатор (вин)

`state` - штат регистрации

`condition` - состояние по шкале (1-5)

`odometer` - пробег в милях

`color` - цвет кузова

`interior` - цвет интерьера

`seller` - продавец

`sellingprice` - стоимость продажи

`saledate` - дата продажи
