# Telegram service description

### Name
    - Telegram gateway service
### Description
    - Сервис обеспечивает взаимодействие пользователя через бот-апи сервиса telegram в привычном для него виде.
### Dependencies
    - flow-service (По запросу получать следующую карточку со словом/уроком. Получать пункты меню)
### Event-subscription (telegram events)
    - start
    - callback_query
### Queries and commands
    - GET: /menu (Получение меню)
    - POST: /next (Получение следующей карточки)
