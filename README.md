1. sudo docker run --network host -it python bash
2. pip install django
3. django-admin startproject app
4. cd app
5. python manage.py runserver
6. (в отдельном терминале)sudo docker run --name test -e POSTGRES_PASSWORD=postgres -p 5432:5432 -e POSTGRES_DB=test -v /home/alexandr/PycharmProjects/test_db_django:/var/lib/postgresql/data postgres
7. apt update
8. apt-get install nano
9. nano app/settings.py
10. редактируем настройки бд ()
11. pip install psycopg2
12. python manage.py runserver