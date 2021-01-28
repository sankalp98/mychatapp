web: daphne chat.asgi:application --port $PORT --bind 0.0.0.0 -v2
chatworker: python3 manage.py runworker --settings-chat.settings -v2