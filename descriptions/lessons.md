# Lessons service description

### Name
    - Lessons service
### Description
    - Сервис по работе с уроками. Работа с уроками слов: текст/аудио/картинки.
### Dependencies
- flow-service (Отдавать по запросу уроки)
  - admin-gateway-service (REST по работе с уроками)
### Event-subscription (telegram events)
### Queries and commands
    - POST: /lesson/upload (Загрузка урока)
    - DELETE: /lesson/:id (Удаление урока)
    - GET: /lesson/:id (Получение урока)
