Сброс отбора товара по категориям на странице "Штукатурные смеси".

* Тестовые данные: 
1. Тестовый сервер - https://test2.stroyrem-nn.ru/
Логин: dev
Пароль: dev557755

2. Продовый сервер -https://stroyrem-nn.ru/

* Предусловия:
1. Открыта страница "Штукатурные смеси" https://test2.stroyrem-nn.ru/catalog/shtukaturnye-smesi (или https://stroyrem-nn.ru/catalog/shtukaturnye-smesi)
2. Нажата кнопка "Фильтр"(тач)

Шаги:
1. Нажать кнопку "На складе".

*Ожидаемый результат:
Отображен товар (штукатурные смеси), присутствующий на складе.

2. В разделе ВИД нажать любую кнопку выбора товара.

*Ожидаемый результат:
Отобран товар по его виду и присутствующий на складе.

3. Нажать кнопку "Сбросить выбор".

*Ожидаемый результат:
Отображен весь товар (штукатурные смеси).

Автор: В.Савин


* Тестовый сервер 

| Дата | Время | Браузер Desktop| Результат/Баг № Trello| Браузер тач| Результат/Баг № Trello| Дата релиза |Имя |
| --- | --- | --- | --- | --- | --- | --- | --- | 
|2023-07-27 | 12:47 | Chrome 114.0.5735.248 | PASS | Samsung Galaxy A50/Chrome 114.0.5735.196 | PASS | 04.07.23 | Наталья К. | 
|2023-07-27 | 12:50 | Yandex 23.7.0.2534 | PASS |  |  | 04.07.23 | Наталья К. |
| 13.08.23 | 01:26 | Chrome версия 114.0.5735.199 Firefox версия 115.0.2 | PASS | Chrome версия 114.0.5735.196 MIUI 12.5.13 | PASS | 13.08.23 | Надежда |  


* Продовый сервер

| Дата | Время | Браузер Desktop| Результат/Баг № Trello| Браузер тач| Результат/Баг № Trello| Дата релиза |Имя |
| --- | --- | --- | --- | --- | --- | --- | --- | 
| 2023-07-27 | 12:48 | Chrome 114.0.5735.248 | FAIL https://trello.com/c/L2aAXVNy/238 | Samsung Galaxy A50/Chrome 114.0.5735.196 | FAIL https://trello.com/c/L2aAXVNy/238 | 04.07.23 | Наталья К. | 
| 2023-07-27 | 12:51 | Yandex 23.7.0.2534 | FAIL https://trello.com/c/L2aAXVNy/238 |  |  | 04.07.23 | Наталья К. |
| 13.08.23 | 23:18 | Chrome версия 114.0.5735.199 Firefox версия 115.0.2 | FAIL https://trello.com/c/L2aAXVNy/238 | Chrome версия 114.0.5735.196 MIUI 12.5.13 | FAIL https://trello.com/c/L2aAXVNy/238 | 13.08.23 | Надежда |  

