# **Название работы: "Простая аукционная система"**

## Описание проекта: 
Веб-приложение по созданию простой аукционной системы, которая позволяет создавать лоты и делать на них ставки.

## Выполнены следующие функциональные требования для проекта:

- Аукцион работает так: Создание лота -> Перевод лота в состояние «Запущены торги» -> Прием ставок по лоту -> Перевод лота в состояние «Торги окончены».
- Текущая цена лота вычисляется на основе стартовой цены и количества ставок на данный лот.
- Ставки делаются через отправку имени ставящего в POST-запросе. 
- В API представлены несколько методов для получения аналитической информации по лотам, а также по работе с лотами и ставками.
- В API предусмотрен экспорт информации по лотам в виде CSV-файла. 
- Миграциями базы данных управляет Liquibase. 
- Все основные действия (создание лота или новой ставки, например) логируются.
- Запросы в БД оптимальны и не вызывают проблему N+1.

## Используемые технологии и библиотеки:

Язык и окружение: Java 17, Spring Boot/Web/JPA, Hibernate, PostgreSQL, Liquibase, Lombok.
Прочее: Swagger
