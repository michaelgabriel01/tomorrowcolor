web: gunicorn config.wsgi:application
worker: celery worker --app=tomorrowcolor.taskapp --loglevel=info
