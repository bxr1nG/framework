# Introduction to Testing

## Функциональное тестирование сайта [Fortrade](https://ready.fortrade.com/)



### 1 *Добавление торговой пары в избранное*

| Название                                                     | Описание                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| **Номер тест-кейса**                                         | 1                                                            |
| **Заголовок**                                                | Добавление пары в избранное                                  |
| **Предусловие**                                              | Открыта страница [Home](https://ready.fortrade.com/#home), реализован вход в аккаунт |
| **Шаг**                                                      | **Ожидаемый результат**                                      |
| В левом меню страницы нажать на выпадающий список "Избранное" | Выпадающий список раскрылся                                  |
| В выпадающем списке нажать на элемент списка "Все"           | Левое меню изменило свое содержание на вкладки с различными инструментами |
| В левом меню нажать на вкладку "Валюта"                      | Вкладка "Валюта" раскрылась, в ней появились вложенные вкладки с инструментами |
| В левом меню во вкладке "Валюта" выбрать вложенную вкладку "Основные валютные пары" | Вложенная вкладка "Основные валютные пары" раскрылась, в ней появились торговые пары |
| В открытой вложенной вкладке нажать на торговую пару "AUD/CAD" | В области графика открылась новая вкладка с графиком "AUD/CAD" |
| В меню графика на открытой вкладке нажать кнопку "Избранное" с символом звезды | В левом меню появилось всплывающее окно с текстом "Инструмент добавлен в ваше избранное" |



### 2 *Создание мультиграфика*

| Название                                                     | Описание                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| **Номер тест-кейса**                                         | 2                                                            |
| **Заголовок**                                                | Создание мультиграфика                                       |
| **Предусловие**                                              | Открыта страница [Home](https://ready.fortrade.com/#home), реализован вход в аккаунт, открыта одна вкладка в области графиков |
| **Шаг**                                                      | **Ожидаемый результат**                                      |
| В левом меню страницы нажать на выпадающий список "Избранное" | Выпадающий список раскрылся                                  |
| В выпадающем списке нажать на элемент списка "Самый популярный" | Левое меню изменило свое содержание на торговые пары         |
| Нажать на первую торговую пару в списке                      | В области графика открылась новая вкладка с графиком нажатой торговой пары |
| В меню графика на открытой вкладке нажать кнопку "Одиночные/мультиграфики" с символом таблицы | Область графика изменила свое содержание на список графиков, находящихся в заголовке области графика |



### 3 *Изменение фамилии и имени в настройках аккаунта*

| Название                                                     | Описание                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| **Номер тест-кейса**                                         | 3                                                            |
| **Заголовок**                                                | Изменение фамилии и имени в настройках аккаунта              |
| **Предусловие**                                              | Открыта страница [Home](https://ready.fortrade.com/#home), реализован вход в аккаунт |
| **Шаг**                                                      | **Ожидаемый результат**                                      |
| Нажать на кнопку с изображением меню в правом верхнем углу экрана | Правое меню раскрылось                                       |
| В открытом меню нажать кнопку "Настройки" с изображением человека и шестеренки внизу экрана | Меню поменяло свое содержание, открылась вкладка "Настройки" |
| В открытой вкладке меню нажать кнопку "Мой профиль и настройки" | Открылось окно "Мой профиль и настройки"                     |
| Нажать на строку "Имя" в открытом окне                       | Открылось окно "Обновить личные данные"                      |
| Очистить поле "Имя"                                          | Поле "Имя" стало пустым                                      |
| Ввести в поле "Имя" строку "Даниэль"                         | В поле "Имя" отображается текст "Даниэль"                    |
| Очистить поле "Фамилия"                                      | Поле "Имя" стало пустым                                      |
| Ввести в поле "Фамилия" строку "БГТУ"                        | В поле "Фамилия" отображается текст "БГТУ"                   |
| Нажать кнопку "Сохранить"                                    | В верхней части экрана появилось всплывающее окно с текстом "The following details were changed :  First name,  Last name" |



### 4 *Скачивание истории сделок*

| Название                                                | Описание                                                     |
| ------------------------------------------------------- | ------------------------------------------------------------ |
| **Номер тест-кейса**                                    | 4                                                            |
| **Заголовок**                                           | Скачивание истории сделок                                    |
| **Предусловие**                                         | Открыта страница [Home](https://ready.fortrade.com/#home), реализован вход в аккаунт, открыта вкладка "AUD/CAD" в области графиков |
| **Шаг**                                                 | **Ожидаемый результат**                                      |
| В нижнем блоке страницы нажать кнопку "Закрытые сделки" | Открылась вкладка "Закрытые сделки"                          |
| Нажать кнопку "Экспорт в Excel" в нижнем блоке страницы | Скачался файл closedtrades.csv                               |



### 5 *Изменение языка сайта*

| Название                                                    | Описание                                                     |
| ----------------------------------------------------------- | ------------------------------------------------------------ |
| **Номер тест-кейса**                                        | 5                                                            |
| **Заголовок**                                               | Изменение языка сайта                                        |
| **Предусловие**                                             | Открыта страница [Home](https://ready.fortrade.com/#home), реализован вход в аккаунт, открыта вкладка "AUD/CAD" в области графиков |
| **Шаг**                                                     | **Ожидаемый результат**                                      |
| В верхнем блоке страницы нажать на кнопку с именем аккаунта | Открылось основное меню                                      |
| В основном меню нажать кнопку "Настройки"                   | В основном меню открылось меню настроек                      |
| Нажать на выпадающий список "Язык"                          | Выпадающий список с доступными языками раскрылся             |
| В выпадающем списке выбрать "English"                       | Страница перезагрузилась, язык сайта изменился на английский |



### 6 *Открытие сделки на сумму больше баланса*

| Название                                             | Описание                                                     |
| ---------------------------------------------------- | ------------------------------------------------------------ |
| **Номер тест-кейса**                                 | 6                                                            |
| **Заголовок**                                        | Открытие сделки на сумму больше баланса                      |
| **Предусловие**                                      | Открыта страница [Home](https://ready.fortrade.com/#home), реализован вход в аккаунт, открыта вкладка "AUD/CAD" в области графиков |
| **Шаг**                                              | **Ожидаемый результат**                                      |
| В заголовке открытого графика нажать кнопку "Купить" | Открылось окно "AUD/CAD"                                     |
| В поле "Сумма" ввести 10,000,000 и нажать Enter      | Поле "Сумма" изменило свое содержание на "1,646,000", внизу окна появилась надпись "Вы собираетесь КУПИТЬ AUD/CAD в размере 1,646,000 AUD", что соответствует эквивалентной сумме денег на аккаунте |
| Нажать кнопку "Купить сейчас"                        | Окно закрылось, появилось всплывающее окно "Вы купили 1,646,000 AUD/CAD по цене  0.92205", в нижнем меню страницы во вкладке "Открыть сделку" появилась запись о новой сделке. |



### 7 *Открытие сделки на нулевую сумму*

| Название                                             | Описание                                                     |
| ---------------------------------------------------- | ------------------------------------------------------------ |
| **Номер тест-кейса**                                 | 7                                                            |
| **Заголовок**                                        | Открытие сделки на нулевую сумму                             |
| **Предусловие**                                      | Открыта страница [Home](https://ready.fortrade.com/#home), реализован вход в аккаунт, открыта вкладка "AUD/CAD" в области графиков |
| **Шаг**                                              | **Ожидаемый результат**                                      |
| В заголовке открытого графика нажать кнопку "Купить" | Открылось окно "AUD/CAD"                                     |
| В поле "Сумма" ввести 0 и нажать Enter               | Поле "Сумма" изменило свое содержание на "0", внизу окна появилась надпись "Вы собираетесь КУПИТЬ AUD/CAD в размере 0 AUD", под полем "Сумма" появилось сообщение "Минимальная сумма сделки равна 1000.". Кнопка "Купить сейчас" поменяла свой цвет на серый |
| Нажать кнопку "Купить сейчас"                        | Ничего не произошло, так как кнопка не активна               |



### 8 *Открытие торговой сделки*

| Название                                             | Описание                                                     |
| ---------------------------------------------------- | ------------------------------------------------------------ |
| **Номер тест-кейса**                                 | 8                                                            |
| **Заголовок**                                        | Открытие торговой сделки                                     |
| **Предусловие**                                      | Открыта страница [Home](https://ready.fortrade.com/#home), реализован вход в аккаунт, открыта вкладка "AUD/CAD" в области графиков. Исходный баланс 12,657.57$ |
| **Шаг**                                              | **Ожидаемый результат**                                      |
| В заголовке открытого графика нажать кнопку "Купить" | Открылось окно "AUD/CAD"                                     |
| В поле "Сумма" ввести 1000 и нажать Enter            | Поле "Сумма" содержит текст "1,000", внизу окна появилась надпись "Вы собираетесь КУПИТЬ AUD/CAD в размере 1,000 AUD" |
| Нажать кнопку "Купить сейчас"                        | Окно закрылось, появилось всплывающее окно "Вы купили 1,000 AUD/CAD по цене  0.92055", в нижнем меню страницы во вкладке "Открыть сделку" появилась запись о новой сделке. Текущий баланс 12,657.57$ - 0.92055$ * 1,000 = 11,737.02$ |



### 9 *Закрытие торговой сделки*

| Название                                                     | Описание                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| **Номер тест-кейса**                                         | 9                                                            |
| **Заголовок**                                                | Закрытие торговой сделки                                     |
| **Предусловие**                                              | Открыта страница [Home](https://ready.fortrade.com/#home), реализован вход в аккаунт, открыта вкладка "AUD/CAD" в области графиков. Есть открытая сделка на 1,000 AUD/CAD. Исходный баланс 11,737.02$ |
| **Шаг**                                                      | **Ожидаемый результат**                                      |
| В нижнем меню страницы во вкладке "Открыть сделку" нажать кнопку "Закрыть сделку" в строке сделки на 1,000 AUD/CAD | Появилось окно с данными о сделке                            |
| Нажать кнопку "Закрыть сделку"                               | Окно закрылось, появилось всплывающее окно "Сделка успешно обновлена". Во вкладке "Закрытые сделки" нижнего меню страницы появилась новая запись о завершенной сделке. Текущий баланс 11,737.02$ + 0.91965$ * 1,000 = 12,656.67$ |



### 10 *Закрыть все активные сделки*

| Название                                                     | Описание                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| **Номер тест-кейса**                                         | 10                                                           |
| **Заголовок**                                                | Закрыть все активные сделки                                  |
| **Предусловие**                                              | Открыта страница [Home](https://ready.fortrade.com/#home), реализован вход в аккаунт, открыта вкладка "AUD/CAD" в области графиков |
| **Шаг**                                                      | **Ожидаемый результат**                                      |
| В заголовке открытого графика нажать кнопку "Купить"         | Открылось окно "AUD/CAD"                                     |
| В поле "Сумма" ввести 1000 и нажать Enter                    | Поле "Сумма" содержит текст "1,000", внизу окна появилась надпись "Вы собираетесь КУПИТЬ AUD/CAD в размере 1,000 AUD" |
| Нажать кнопку "Купить сейчас"                                | Окно закрылось, появилось всплывающее окно "Вы купили 1,000 AUD/CAD по цене  0.92055", в нижнем меню страницы во вкладке "Открыть сделку" появилась запись о новой сделке. |
| Повторить предыдущие шаги                                    | В нижнем меню страницы во вкладке "Открыть сделку" появилась вторая запись. |
| В нижнем меню на вкладке "Открыть сделку" нажать на кнопку "Закрыть все сделки" | Открылось окно "Закрыть все сделки"                          |
| Нажать на кнопку "Закрыть все сделки", находящуюся в окне    | Окно закрылось. Во вкладке "Закрытые сделки" нижнего меню страницы появилась новая запись о завершенной сделке. Из вкладки "Открыть сделку" пропали записи |

