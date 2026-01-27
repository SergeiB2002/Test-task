# Задание 2: проектирование API
## 1. Пример REST API запроса

Метод: ```GET```

URL: ```/api/v1/partners/stores```

**Параметры запроса:**
- ```latitude``` (number, optional): Географическая широта местоположения пользователя.
- ```longitude``` (number, optional): Географическая долгота местоположения пользователя.
- ```limit``` (integer, optional): Максимальное количество магазинов в ответе (для пагинации). По умолчанию, например, 20.

**Пример запроса:**
```
GET /api/v1/partners/stores?latitude=45.1234&longitude=38.9865&limit=10
Accept: application/json
Authorization: Bearer <user_access_token>
```
