# yamdb_final
![Status of project](https://github.com/AkuLinker/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg)
### Описание
Проект для организации базы данных с отзывами на различные произведения искуства через api на основе RestAPI.
### Технологии
Python\
Django\
Django REST framework\
Docker
### Перед запуском проекта
```
docker-compose exec web python manage.py migrate
docker-compose exec web python manage.py collectstatic
```

### Примеры запросов
- Получение списка всех произведений
```
http://host/api/v1/titles/
```
- Получение списка всех жанров
```
http://host/api/v1/genres/
```
- Получение списка всех категорий
```
http://host/api/v1/categories/
```
- Получение списка всех отзывов на произведение
```
http://host/api/v1/titles/{title_id}/reviews/
```
- Вся Информация
```
http://host/redoc/
```
### Авторы
- [Иван](https://github.com/AkuLinker/ "GitHub аккаунт")
