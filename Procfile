web: daphne LmsApi.asgi:application --port $PORT --bind 0.0.0.0 -v2
chatworker: python manage.py runworker channels --settings=LmsApi.settings -v2