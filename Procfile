#Procfile
web: ddtrace-run gunicorn app:app -b 0.0.0.0:$PORT --access-logfile -
background: python worker.py