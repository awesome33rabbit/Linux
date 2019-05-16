```ps -aux```

```pgrep supervisord```

```gunicorn /root/sztt/working/sztt.wsgi --bind 0.0.0.0:9988```

```gunicorn -b 0.0.0.0:9988 sztt.wsgi:application```

```kill -s 9 1722```

```supervisorctl```

```sudo supervisord -c /etc/supervisord/supervisord.conf```
