web: python3.7 manage.py runserver 0.0.0.0:$PORT --noreload
web: gunicorn praisetheflesh.wsgi:application --log-file -
heroku ps:scale web=1
