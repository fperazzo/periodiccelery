web: gunicorn cfehome.wsgi --log-file -
worker: celery -A cfehome worker --beat -S django --l info