# BS Private Server Database (MySQL)

Пустая схема базы данных для приватного сервера Brawl Stars.

## ❗ Требования

- MySQL 8.0
- Права на создание БД

## 💾 Установка

### 1. Создай базу данных

```sql
CREATE DATABASE tq_server;
USE tq_server;
```

### 2. Импортируй схему

```bash
mysql -u root -p tq_server < database.sql
```
