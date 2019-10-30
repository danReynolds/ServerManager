Updating Certs:

```
docker-compose run letsencrypt certonly
Check if put it as the right one in /etc/nginx/letsencrypt, might have duplicated it, in which case remove the 2nd one and make the primary name the new one
```
