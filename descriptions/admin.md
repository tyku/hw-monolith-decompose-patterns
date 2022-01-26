# Admin service description

### Name
    - Admin service
### Description
    - Админка для авторов. Rest для загрузки контента словарей и уроков.
### Dependencies
    - dictionary-service
    - lessons-service
### Event-subscription (telegram events)
### Queries and commands
    - POST: /word/upload
    - POST: /lesson/upload
    - DELETE: /word/:id 
    - DELETE: /lesson/:id 
    - GET: /word/:id 
    - GET: /lesson/:id 
