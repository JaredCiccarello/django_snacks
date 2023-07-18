
pip3 install
pytest
django

Virtual Environment
python3 -m venv .venv

Start project
django-admin startproject snacks_project .
  Without the . this creates two folders

Run server
python3 manage.py runserver
  Make sure you upgrade pip

This gets your database ready to run
python3 manage.py migrate


python3 manage.py startapp things

pip install django-compressor

Links
Website
http://127.0.0.1:8000/

http://127.0.0.1:8000/admin/login/?next=/admin/

