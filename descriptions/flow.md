# Flow service description

### Name
    - Flow service
### Description
    - Сервис управляет пользовательскими сценариями. Очередность, конетен карточки. Так же выполняет роль оркестратора для зависящих сервисов.
### Dependencies
    - dictionary-service
    - lessons-service
### Event-subscription (telegram events)
### Queries and commands
    - POST: /word/next (Получение следующего слова)
    - POST: /lessons/next (Получение следующего урока)
    - GET: /menu (Получение следующего урока)
