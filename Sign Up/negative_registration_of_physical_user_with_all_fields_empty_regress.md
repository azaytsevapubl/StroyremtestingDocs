Regfiz02

Регистрация нового пользователя (физическое лицо) с пустыми полями

* Тестовые данные: 

* Предусловия:
  
  Открыта главная страница прода [https://stroyrem-nn.ru/](https://stroyrem-nn.ru/) или теста [https://test2.stroyrem-nn.ru/](https://test2.stroyrem-nn.ru/)

* Шаги:
1. Нажать на иконку "Профиль" (десктоп) или на бургер меню (тач)

2. Нажать на кнопку "Регистрация"

3. Оставить поля пустыми и нажать кнопку "Зарегистрироваться"
* Ожидаемый результат: 
  
  Обязательные поля с астериксом обрамлены красной рамкой и надписью "Необходимо заполнить данное поле".
  Текст полей читабельный и не накладывается на другие надписи

* Постусловие: удалить тестовые данные

Автор: Татьяна Жукаускене

Отчет о тестировании

Тестовый сервер

| Дата       | Время | Версия браузера Десктоп                                 | Результат/Баг в Трелло Десктоп     | Версия браузера и ОС Тач         | Результат/Баг в Трелло Тач         | Дата релиза | QA      |
| ---------- | ----- | ------------------------------------------------------- | ---------------------------------- | -------------------------------- | ---------------------------------- | ----------- | ------- |
| 2023-08-25 | 18:10 | Chrome 116.0.5845.111 (64-bit) Firefox 116.0.3 (64-bit) | FAIL https://trello.com/c/yujXCdJJ | Chrome 116.0.5845.92, Android 10 | FAIL https://trello.com/c/yujXCdJJ | 13.08.2023  | Татьяна |
|            |       |                                                         |                                    |                                  |                                    |             |         |

Продовый сервер

| Дата       | Время | Версия браузера Десктоп                                 | Результат/Баг в Трелло Десктоп     | Версия браузера и ОС Тач         | Результат/Баг в Трелло Тач         | Дата релиза | QA      |
| ---------- | ----- | ------------------------------------------------------- | ---------------------------------- | -------------------------------- | ---------------------------------- | ----------- | ------- |
| 2023-08-25 | 18:15 | Chrome 116.0.5845.111 (64-bit) Firefox 116.0.3 (64-bit) | FAIL https://trello.com/c/yujXCdJJ | Chrome 116.0.5845.92, Android 10 | FAIL https://trello.com/c/yujXCdJJ | 13.08.2023  | Татьяна |
|            |       |                                                         |                                    |                                  |                                    |             |         |
