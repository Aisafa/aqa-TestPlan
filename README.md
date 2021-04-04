## 1. Перечень автоматизируемых сценариев

### Поле Имя

* Ввод валидных значений (Айдар);
* Ввод латинских символов (Aidar);
* Ввод цифр в (123, Айдар12);
* Ввод пустого значения ( );
* Ввод текста с дефисом (Айдар-дар) ;
* Ввод спец.символов (@#%$);
* Вставка скопированного текста;
* Ввод точки после имени (Айдар.);
* Вставка пробела перед текстом и после ( Айдар );
* Ввод граничных значений (1 символ, максимально допустимый, и свыше максимально допустимого).

### Поле Телефон

* Ввод валидных значений (+79999999999);
* Ввод латинских символов (seven nine nine nine);
* Ввод цифр и символов в (Айдар12);
* Ввод пустого значения ( );
* Ввод цифр с дефисом (8-999-999-99-99) ;
* Ввод спец.символов (@#%$);
* Вставка скопированного номера;
* Ввод точки после номера (+79999999999.);
* Вставка пробела перед текстом и после ( +79999999999 );
* Ввод граничных значений (1 символ, 12 символов).

## 2. Перечень используемых инструментов с обоснованием выбора

* IntelliJIDEA - интегрированная среда разработки программного обеспечения на Java;
* Gradle - система автоматической сборки для тестов;
* JunitJupiter – платформа для запуска тестов;
* Selenide - фреймворк для автоматизированного тестирования веб-приложений на основе SeleniumWebDriver.

> Выбраны наиболее часто используемые, популярные и универсальные инструменты:

## 3. Перечень необходимых разрешений/данных/доступов от банка (предоставлять доступ к СУБД или давать собранную версию сервиса, вам, естественно, не будут)

* Получить функциональные требования.
* Получить jar-файл со страницей ввода данных.

## 4. Перечень и описание возможных рисков при автоматизации

**Трудно воспроизводимые кейсы, которые не могут быть обнаружены в тестовой среде:**

* Падение системы при массовом одновременном подключении;
* Потеря данных при обрыве связи с банком в момент совершения операции.

## 5. Перечень необходимых специалистов для автоматизации

* Аналитик-для формирования требований;
* QA инженер-для разработки и проведения тестов.

## 6. Интервальная оценка с учётом рисков (в часах)

3 часа на проектирование основных data классов с элементами Selenide; 6 часов на проектирование и разработку, и прогон
тестовых классов.
