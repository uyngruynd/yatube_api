# YaTube API

## Описание
Проект «API для Yatube» подготовлен для изучения базовых принципов построения 
API на основе фреймворка [DRF]

## Технологии:
- Python 3.7.9
- Django 2.2.16
- DRF 3.12.4

## Примеры:
 
Получение публикаций

```
GET api/v1/posts/
```

Получение комментариев

```
 GET api/v1/posts/{post_id}/comments/{id}/
```

Получение сообществ

```
GET api/v1/groups/
```

Подробное описание в формате ReDoc доступно [тут] 

[DRF]: <https://www.django-rest-framework.org/>
[тут]: <http://127.0.0.1:8000/redoc/>
