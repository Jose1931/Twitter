web: gunicorn twitter.wsgi:application --log-file - --log-level debug 
python manage.py collectstatic --noinputable
manage.py migrate