## 最初の一歩

```
docker-compose up -d workspace php-fpm nginx postgres mailhog minio
```

## お片付け

滅びの呪文。

```
$ docker-compose down --rmi all --volumes --remove-orphans
```
