# Dictionary service description

### Name
    - Dictionary service
### Description
    - Сервис по работе со словарями. Работа с контентом слов: текст/аудио/картинки.
### Dependencies
    - flow-service (Отдавать по запросу слова)
    - admin-gateway-service (REST по работе со словами)
### Event-subscription (telegram events)
### Queries and commands
    - POST: /word/upload (Загрузка слов)
    - DELETE: /word/:id (Удаление слов)
    - GET: /word/:id (Получение слов)
