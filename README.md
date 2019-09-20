# in mysite folder open cmd
C:\Users\YourName\Desktop\mysite>

# follow step by step for working successfully with this project
1) pip install django==2.1.4
2) python manage.py makemigrations
3) python manage.py migrate
4) python manage.py createsuperuser

        Username (leave blank to use 'YourName'): Enter Username
        Email address: Enter mail
        Password: Enter Password
        Password (again): Enter Password again
        Superuser created successfully.
        
When you will access to admin page for example in localhost
http://127.0.0.1:8000/admin
you have to enter username and password from above 

5) python -m pip install django-tinymce4-lite.
6) python manage.py runserver
