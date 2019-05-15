web: uwsgi --ini=uwsgi.ini --http=0.0.0.0:$PORT
worker: SENTRY_CONF=sentry.conf.py sentry run worker
beat: SENTRY_CONF=sentry.conf.py sentry run cron
