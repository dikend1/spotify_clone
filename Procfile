release: python manage.py makemigrations
release: python manage.py migrate
web: gunicorn clone.wsgi --log-file