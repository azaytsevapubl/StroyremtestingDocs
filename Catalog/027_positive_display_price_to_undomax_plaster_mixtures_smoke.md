Отображение товара с немаксимальной ценой на странице "Штукатурные смеси".

* Тестовые данные: 
1. Тестовый сервер - https://test2.stroyrem-nn.ru/
Логин: dev
Пароль: dev557755

2. Продовый сервер -https://stroyrem-nn.ru/

* Предусловия:
Открыта страница "Штукатурные смеси" https://test2.stroyrem-nn.ru/catalog/shtukaturnye-smesi (или https://stroyrem-nn.ru/catalog/shtukaturnye-smesi)

* Шаги:
1. Отсортировать товар по убыванию цены.
2. Нажата кнопка "Фильтр" (тач)
3. В поле "до" ввести стоимость меньше, чем у товара с максимальной ценой;
4. Нажата кнопку "Показать ... товара" (тач)
5. Нажать Enter

*Ожидаемый результат:
Товар с максимальной ценой не отображен.

Автор: В.Савин


* Тестовый сервер 

| Дата | Время | Браузер Desktop| Результат/Баг № Trello| Браузер тач| Результат/Баг № Trello| Дата релиза |Имя |
| --- | --- | --- | --- | --- | --- | --- | --- | 
|2023-07-26 | 14:37 | Chrome 114.0.5735.248 | PASS | Samsung Galaxy A50/Chrome 114.0.5735.196 | PASS | 04.07.23 | Наталья К. | 
|2023-07-26 | 14:40 | Yandex 23.5.4.674 | PASS |  |  | 04.07.23 | Наталья К. |
| 12.08.23 | 20:20 | Chrome версия 114.0.5735.199 Firefox версия 115.0.2 | PASS | Chrome версия 114.0.5735.196 MIUI 12.5.13 | PASS | 16.06.23 | Надежда |  


* Продовый сервер

| Дата | Время | Браузер Desktop| Результат/Баг № Trello| Браузер тач| Результат/Баг № Trello| Дата релиза |Имя |
| --- | --- | --- | --- | --- | --- | --- | --- | 
| 2023-07-26 | 14:38 | Chrome 114.0.5735.248 | PASS | Samsung Galaxy A50/Chrome 114.0.5735.196 | PASS | 04.07.23 | Наталья К. | 
| 2023-07-26 | 14:41 | Yandex 23.7.0.2534 | PASS |  |  | 04.07.23 | Наталья К. |
| 13.08.23 | 22:50 | Chrome версия 114.0.5735.199 Firefox версия 115.0.2 | PASS | Chrome версия 114.0.5735.196 MIUI 12.5.13 | PASS | 13.08.23 | Надежда |  