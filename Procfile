release: python manage.py make migrations && python manage.py migrate
web: gunicorn drf_api.wsgi