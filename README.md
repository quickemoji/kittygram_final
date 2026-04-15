# Описание проекта

Проект помогает пользователям публиковать своих котиков и делиться ими с другими.

## Возможности

- просмотр котиков, добавленных пользователями;
- добавление своих котиков с указанием:
  - фотографии;
  - цвета;
  - года рождения;
  - великих достижений.

## Стек технологий

- Python
- Django
- Django REST Framework
- Djoser
- PostgreSQL
- psycopg2-binary
- Pillow
- React
- JavaScript
- CSS Modules
- Docker
- Docker Compose
- Nginx
- Gunicorn
- pytest
- pytest-django
- Ruff
- pycodestyle
- PyYAML

## Как развернуть проект

1. Заполните файл `.env` на основе `.env.example`.

2. Создайте Docker Volume:
   ```bash
   docker volume create pg_data
   docker volume create static
   docker volume create media
   ```

3. Запустите проект:
   ```bash
   docker compose up --build
   ```

## Остановить проект
```
docker compose down
```