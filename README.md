DigitalPunk blog
================================

Launching
--------------
In two separate terminals...


**1st Terminal**
```
cd frontend
yarn
yarn serve
```

**2nd Terminal** 

with virtualenv activated:

```
pip install -r requirements.txt
python manage.py createsuperuser (only run once!)
python manage.py migrate (you might need to run this first if no DB set up)
python manage.py runserver
```

Access the site at http://127.0.0.1:8000
