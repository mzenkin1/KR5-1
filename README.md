Парсер вакансий с сайта HH.RU

Собирает по 100 вакансий из 11 кампаний (возможно расширить, 
добавив id компании в список ID_COMPANY на 6 строке файла main.py) таблицы загружаются автоматически.

Затем следуем меню, вводя цифры, соответсвующие меню. Не верный ввод обрабатывается

При выгрузке на локальный ПК, создать в корне каталога файл database.ini В файле database.ini указать 
свои параметры подключения в виде [postgresql] host=localhost user=postgres password=qwerty port=5432 

