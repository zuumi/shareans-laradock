## 最初の一歩

```
$ export HOSTNAME=my-minio-localhost-alias
$ docker-compose up -d
```

## お片付け

滅びの呪文。

```
$ docker-compose down --rmi all --volumes --remove-orphans
```

## minioでS3ローカル開発環境を高築する

### 参考

https://hub.docker.com/r/minio/minio/
https://www.ritolab.com/entry/232
https://www.burgundywall.com/post/upload-minio-curl
https://qiita.com/reflet/items/3e0f07bc9d64314515c1

## s3-clientを導入

下記サイトを完コピ。

* https://stackoverflow.com/questions/56627446/docker-compose-how-to-use-minio-in-and-outside-of-the-docker-network/61214488#61214488

## minio文法は下記を参照

（記載予定。）