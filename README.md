# BS Private Server Database (MySQL)

Пустая схема базы данных для приватного сервера Brawl Stars.

## ❗ Требования

- MySQL 8.0
- Права на создание БД

## 💾 Установка

### 1. Создай базу данных

```sql
CREATE DATABASE brawl_server;
USE brawl_server;

mysql -u root -p brawl_server < database.sql
