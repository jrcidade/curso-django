release: python manage.py migrate --noinput
web: newrelic-admin run-program gunicorn pypro.wsgi --log-file -