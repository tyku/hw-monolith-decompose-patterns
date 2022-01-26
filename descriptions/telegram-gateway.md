# Telegram service description

### Name
    - Telegram gateway service
### Description
    - Сервис обеспечивает взаимодействие пользователя через бот-апи сервиса telegram в привычном для него виде.
### Dependencies
    - flow-service
### Event-subscription (telegram events)
    - start
    - callback_query
### Queries and commands
    - GET: /menu (Получение меню)
    - POST: /next (Получение следующей карточки)
