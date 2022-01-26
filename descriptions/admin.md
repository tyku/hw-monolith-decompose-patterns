# Admin service description

### Name
    - Admin service
### Description
    - Админка для авторов. Rest для загрузки контента словарей и уроков.
### Dependencies
    - dictionary-service (Нужно уметь получать/удалять/добавлять слова)
    - lessons-service (Нужно уметь получать/удалять/добавлять уроки)
### Event-subscription (telegram events)
### Queries and commands
    - POST: /word/upload (Загрузка слов)
    - POST: /lesson/upload (Загрузка уроков)
    - DELETE: /word/:id (Удаление слова)
    - DELETE: /lesson/:id (Удаление урока) 
    - GET: /word/:id (Получение слова)
    - GET: /lesson/:id (Получение урока)
