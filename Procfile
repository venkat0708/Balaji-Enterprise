web: gunicorn config.wsgi:application
worker: celery worker --app=balaji.taskapp --loglevel=info
