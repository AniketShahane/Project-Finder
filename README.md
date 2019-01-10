# Project-Finder
- git clone https://github.com/djunicode/Project-Finder.git
- cd Project-Finder
- virtualenv env --no-site-packages
- source env/bin/activate
- pip install -r requirements.txt
- Create a postgres db and add the credentials to settings.py
- python manage.py makemigrations
- python manage.py migrate
- python manage.py runserver

