# Проект "КупиПодариДай"

## Описание

"КупиПодариДай" — это веб-сервис, разработанный студентом Яндекс Практикума **Зайцевым Павлом**, который позволяет пользователям делиться своими желаниями и создавать списки подарков. Этот проект включает в себя как фронтенд, так и бэкенд части приложения.

Проект докеризирован и может быть легко развернут с помощью Docker и Docker Compose.

## Развернутые версии приложения

- **Frontend**: [https://puvli.nomorepartiesco.ru/](https://puvli.nomorepartiesco.ru/)
- **Backend**: [https://api.puvli.nomorepartiesco.ru/](https://api.puvli.nomorepartiesco.ru/)

### IP-адрес сервера:

- **84.201.156.130**

## Структура репозитория

- `frontend/` — исходный код фронтенд части приложения.
- `backend/` — исходный код бэкенд части приложения.
- `docker-compose.yml` — конфигурация Docker Compose для запуска проекта.

## Технологии

### Фронтенд:

- React.js
- HTML/CSS
- JavaScript
- Docker

### Бэкенд:

- NestJS (Node.js framework)
- PostgreSQL
- TypeORM
- Docker

### Инфраструктура:

- Docker
- Docker Compose
- Nginx
- PostgreSQL
- Adminer

## Как запустить проект локально

1. **Клонируйте репозиторий:**

   ```bash
   git clone https://github.com/Puvli/docker-and-compose.git

   ```

2. **Перейдите в директорию проекта:**

   ```bash
   cd docker-and-compose

   ```

3. **Создайте файл .env в корневой директории и заполните его следующими переменными:**

   POSTGRES_HOST=postgres
   POSTGRES_USER=student
   POSTGRES_PASSWORD=student
   POSTGRES_DB=kupipodariday
   JWT_SECRET=your_jwt_secret_key

4. **Запустите Docker Compose:**

   docker-compose up --build

   ```

   ```

5. **Откройте приложение:**

Фронтенд будет доступен по адресу: http://localhost:8080
Бэкенд будет доступен по адресу: http://localhost:4000
Adminer для управления базой данных: http://localhost:8081

```

```
