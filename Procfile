web: newrelic-admin run-program gunicorn --pythonpath="$PWD/geopolls-rest" wsgi:application
worker: python geopolls-rest/manage.py rqworker default