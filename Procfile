web: gunicorn -b 0.0.0.0:$PORT example:app --log-file -
worker: python example.py -P $PORT