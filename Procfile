release: python leadmanager/manage.py migrate
web: gunicorn leadmanager.wsgi --log-file -
web: python leadmanage.py runserver