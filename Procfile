web: gunicorn GeoDeer.wsgi --log-file - 

web: python manage.py migrate && gunicorn GeoDeer.wsgi