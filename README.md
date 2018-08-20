# PHP-23-DP-FAQ


Diploma work of Netology «PHP/SQL: back-end» (php-23) course. 
Client part and administrate interface for web service of questions and answers.

Дипломная работа по курсу «PHP/SQL: back-end разработка и базы данных».
Разработать типовой сервис вопросов и ответов. Должна быть реализована клиентская часть сервиса и интерфейс администратора.

Инструкция по установке и первому запуску:

1. Установить composer (https://getcomposer.org)
2. Клонировать репозиторий проекта
3. Установить необходимые пакеты (composer install)
4. Восстановить из дампа faq.sql содержимое базы данных
5. В файле config.php отредактировать данные для подключения к базе данных
6. Настроить веб сервер - обращение осуществляется к файлу index.php в корне проекта:
    - .../index.php - список вопросов и ответов (клиентская часть)
    - .../index.php?/login/ или .../?/login/ - форма авторизации для входа в интерфейс администратора
7. Ссылки на опубликованный проект:
    - гость http://university.netology.ru/u/balabanov/php-23-faq/index.php
    - админ http://university.netology.ru/u/balabanov/php-23-faq/index.php?/login/
8. UML схема базы данных в файле faq_bd_uml.png
9. Описание проекта https://docs.google.com/document/d/1jvdVgYx7ETmW0bHwFFr9qtunkV-ADI2y3SMcPXnlWIo/edit?usp=sharing
(PHP-23-DP-FAQ.txt)  