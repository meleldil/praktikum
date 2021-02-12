# Проект "Увеличение выручки интернет-магазина"

## Данные

**Описание данных**

Таблица `hypothesis`:
- `Hypothesis` — краткое описание гипотезы
- `Reach` — охват пользователей по 10-балльной шкале
- `Impact` — влияние на пользователей по 10-балльной шкале
- `Confidence` — уверенность в гипотезе по 10-балльной шкале
- `Efforts` — затраты ресурсов на проверку гипотезы по 10-балльной шкале

Таблица `orders`:
- `transactionId` — идентификатор заказа
- `visitorId` — идентификатор пользователя, совершившего заказ
- `date` — дата, когда был совершен заказ
- `revenue` — выручка заказа
- `group` — группа A/B-теста, в которую попал заказ.

Таблица `visitors`:
- `date` — дата
- `group` — группа A/B-теста
- `visitors` — количество пользователей в указанную дату в указанной группе A/B-теста.

## Задача

1. Приоритизировать имеющиеся гипотезы.
2. Проанализировать данные A/B-теста.  

## Используемые библиотеки
- *pandas*
- *numpy*
- *matplotlib*
- *seaborn*
- *scipy*