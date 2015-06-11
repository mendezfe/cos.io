# COS-Site

<h3>Installation </h3>

$ pip install -r requirements.txt

$ python manage.py runserver

visit http://127.0.0.1:8000

<h3>Run as Admin </h3>

$ python manage.py runserver

visit http://127.0.0.1:8000/admin

<h3>Getting the Secret key</h3>

Go to mysite and change default_local_settings.py to local_settings.py.

SECRET_KEY = ""       <-----   ask the author for accessing admin page

NEVERCACHE_KEY = ""  <-----   ask the author for accessing admin page
