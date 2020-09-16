# grafana-nginx

### Configure

* Copy etc/nginx/ to /etc/nginx/
* Update /etc/nginx/sites-enabled/grafana.conf
    * ssl_certificate 
    * ssl_certificate_key 
* Copy docker-compose.yml, the location doesn't matter
* Remove ssl configuration from /etc/grafana/grafana.ini
    
### Run in Foreground

```
    docker-compose up
```

### Run in Background

```
    docker-compose up -d
```

### Stop All Containers 

```
    docker-compose down
```