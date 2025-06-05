# Docker Compose Demo

## Сервисы:

- `logger` — пишет лог в volume `/logs/info.log`
- `nginx` — отдает статику на порту 8080

## Запуск

```bash
docker-compose up --build
