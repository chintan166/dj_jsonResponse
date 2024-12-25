python3 -m venv env

source env/bin/activate

pip install django

django-admin startproject watchmate

cd watchmate

python3 manage.py startapp watchlist_app

python3 manage.py  makemigrations

python3 manage.py migrate

python3 manage.py createsuperuser


========================================================================================

![image](https://github.com/user-attachments/assets/94465a69-b773-464f-a125-47151f6a5f8a)
