## Web Project for Tinkoff Bank Learning


### Реализовано

* Верстка главной страницы (https://dsamokhina.github.io/web-project/web/index.html)
* Верстка формы регистраци (https://dsamokhina.github.io/web-project/web/registration.html)
* Верстка формы авторизации (https://dsamokhina.github.io/web-project/web/login.html)
    * Проверка введенных данных на уровне JS
* Форма добавления транзакции и форма счетов пользователя (https://dsamokhina.github.io/web-project/web/transaction.html)
    * Переключатель Расход/Доход
    * Получение данных о состоянии счета
    * Отображение данных в виде таблицы
    * Отображение данных в виде диаграммы HighCharts
* Форма аналитики по счетам с графиками (https://dsamokhina.github.io/web-project/web/analyze.html)
    * Получение данных о транзакции
    * Список транзакций за январь
    * Поиск, работающий по полям (магазин, адрес, дата)
    
### Используется


* Разработка
    * JADE - шаблонизатор
    * SCSS - CSS препроцессор
    * light-server - npm для запуска локального сервера
    * http://beta.json-generator.com/ - для генерации тестовых данных

* Баузер:
    * jQuery
        * ajax запросы
        * поиск элементов, изменение
        * шаблонизатор (?)
    * Highcharts  
        * диаграммы
    * TwitterBootstrap
        * стили для табличек
        * табы (стили + переключение)