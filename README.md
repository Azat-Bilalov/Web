# Разработка Интернет Приложений (РИП) 2022

## Лекции
### Бекенд
Лекция 1. Общая лекция про Web, история, понятия, состав команды, взаимодействие. 

Лекция 2. Шаблонизация, Django

Лекция 3. Базы данных, ER, PostgreSQL. ORM

Лекция 4. Админка Django. Курсоры

Лекция 5. Веб-сервис. Swagger. Микросервисы

Лекция 6. Работа в git. Примеры специализированных сервисов - S3, уведомления, очереди

### Фронтенд
Лекция 7. HTML, CSS, JS. Общие понятия frontend

Лекция 8. React, навигация, TypeScript. 

Лекция 9. Ajax, запросы на React

Лекция 10. Redux. WebSocket

Лекция 11. Авторизация, токены, хранилище сессий. 

Лекция 12. SSO. Ограничение прав на части приложения. 

### Мобильные приложения

Лекция 13. Общая лекция про мобильные приложения. Верстка

Лекция 14. Конкретные кейсы с примерами кода. Сетевое взаимодействие. 

Лекция 15. Деплой в облако, настройка ci/cd

## Лабораторные работы
У каждого своя предметная область на весь курс: бронирование отелей, билетов в театр/кинотеатр, онлайн-магазин

Основной вариант лаб по беку - это Django. Но есть ещё варианты на Go, Java и может Node.js

#### Лабораторная работа №1
Базовая шаблонизация в Django для словаря. Создание базового интерфейса. 

На выбор Django, Go, Spring, Node.js

* [Методические указания](https://github.com/iu5git/web-2022/blob/main/tutorials/lab1/lab1_tutorial.md)

#### Лабораторная работа №2
Создание базы данных PostgreSQL (таблица словаря, таблица фактов с датами и статусом, три даты и менеджер), подключение к шаблонизатору. Создание админки

Статусы: введен, в работе, завершён, удалён

Методические указания:
* [Python](https://github.com/iu5git/web-2022/blob/main/tutorials/lab2/python/lab2_tutorial.md)
* [Golang](https://github.com/iu5git/web-2022/blob/main/tutorials/lab2/golang/README.md)

#### Лабораторная работа №3
Создание веб-сервиса для получения данных из БД. Проверка в swagger. 

* [Методические указания](https://github.com/iu5git/web-2022/blob/main/tutorials/lab3/lab3_tutorial.md)

#### Лабораторная работа №4
Базовая лаба по фронтенду. Карточки элементов, typescript, навигация. Автоскрол

На выбор React, Vue

* [Методические указания](https://github.com/iu5git/web-2022/blob/main/tutorials/lab4/lab4_tutorial.md)

#### Лабораторная работа №5
Добавление Ajax-запросов, redux. Подключение фронтенда к веб-сервису

На выбор React, Vue

* [Методические указания](https://github.com/iu5git/web-2022/blob/main/tutorials/lab4/lab4_tutorial.md)

#### Лабораторная работа №6
Добавление страницы просмотра для таблицы фактов (корзина товаров, бронирования) и окна добавления. Добавление фильтрации и поиска на странице словаря. Подключение к нужным сервисам. 

#### Лабораторная работа №7
Таблица пользователей, авторизация, регистрация, хранение сессий, токены. Автозаполнение пользователей в таблице фактов. 

Подключение SSO?? для авторизации пользователей.

#### Лабораторная работа №8
Создание мобильного приложения с подключением к web-сервису. Просмотр 
товаров, без бронирования и редактирования. 

* [iOS (Swift)](https://github.com/iu5git/web-2022/blob/main/tutorials/android_tutorial/android_tutorial.md)
* [Android (Java)](https://github.com/iu5git/web-2022/blob/main/tutorials/ios_tutorial/ios_tutorial.md)

## Домашнее задание
Добавление роли менеджера контента, доработка под эту роль фронта и сервиса (редактирование таблицы словаря, изменение статусов таблицы фактов, фильтрация фактов). Доработка ролевой модели - ограничение прав на интерфейс

Оформление единого отчёта с диаграммой прецедентов, ER диаграммой, развёртывания для всех лаб и ДЗ
