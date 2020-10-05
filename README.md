# Проект по реализации REST API для социальной сети Yatube с помощью инструментов Django Rest Framework
**Установка:**

Склонируйте репозиторий

`git clone https://github.com/sh4rpy/api_final_yatube.git`

Установите зависимости

`pip install -r requirements.txt`

**Запросы:**

```
/api/v1/posts/ - получить список всех пубоикаций (GET)
/api/v1/posts/ - создать новую публикацию (POST)
/api/v1/posts/{post_id}/ - получить публикацию по id (GET)
/api/v1/posts/{post_id}/ - обновить публикацию по id (PUT)
/api/v1/posts/{post_id}/ - частично обновить публикацию по id (PATCH)
/api/v1/posts/{post_id}/ - удалить публикацию по id (DELETE)

/api/v1/posts/{post_id}/comments/ - получить список всех комментариев публикации (GET)
/api/v1/posts/{post_id}/comments/ - создать новый комменатрий для публикации (POST)
/api/v1/posts/{post_id}/comments/{comment_id}/ - получить комментарий для публикации по id (GET)
/api/v1/posts/{post_id}/comments/{comment_id}/ - получить комментарий для публикации по id (GET)
/api/v1/posts/{post_id}/comments/{comment_id}/ - обновить комментарий для публикации по id (PUT)
/api/v1/posts/{post_id}/comments/{comment_id}/ - частично обновить комментарий для публикации по id (PATCH)
/api/v1/posts/{post_id}/comments/{comment_id}/ - удалить комментарий для публикации по id (DELETE)

/api/v1/token/ - получить JWT-токен (POST)
/api/v1/token/refresh/ - обновить JWT-токен (POST)

/api/v1/follow/ - получить список всех подписчиков (GET)
/api/v1/follow/ - создать подписку (POST)

/api/v1/group/ - получить список всех групп (GET)
/api/v1/group/ - создать новую группу (POST)
```
