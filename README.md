# BS Private Server Database (MySQL)

Пустая схема базы данных для приватного сервера Brawl Stars.

## Требования

- MySQL 8.0
- Права на создание БД

## Установка

1. Создайте базу данных:

CREATE DATABASE brawl_server;
USE brawl_server;

2. Импортируйте схему:

mysql -u root -p brawl_server < database.sql

## Структура таблиц

Таблица accounts: Id, Trophies, Data (JSON), login, password
Таблица alliances: Id, Name, Trophies, Data (JSON)

## Disclaimer

Пустой шаблон. Никаких реальных данных Supercell. Для образовательных целей.
