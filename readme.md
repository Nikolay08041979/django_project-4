# [Домашнее задание №4 "Работа с ORM, 2 часть"](https://github.com/netology-code/dj-homeworks/tree/video/2.2-databases-2)

## [Миграции](https://github.com/netology-code/dj-homeworks/tree/video/2.2-databases-2/orm_migrations)

### Функционал:

✅ Применить текущую миграцию и загрузить исходные данные из файла school.json с помощью loaddata
 
✅ Поменять отношения моделей Student и Teacher с Foreign key на Many to many. Выполнить новые миграции

❌ Поправить шаблон списка учеников с учётом изменения моделей

❌ Проанализировать число SQL-запросов (для каждого студента отдельный запрос) с помощью django-debug-toolbar оптимизированное с помощью [prefetch_related](https://docs.djangoproject.com/en/3.2/ref/models/querysets/#prefetch-related)

### Измененя внесены:
✅ [school/modele.py](https://github.com/Nikolay08041979/django_project-3/blob/master/2.1-databases/work_with_database/phones/models.py)

✅ [school/admin.py](https://github.com/Nikolay08041979/django_project-3/blob/master/2.1-databases/work_with_database/phones/models.py)