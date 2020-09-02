とりあえずDBをPHPMyAdminで見えるようにしただけ
`initdb.d` にsqlファイルを置くと起動時に実行してくれる

docker-compose up -d したら、http://localhost:8080 で見える

```
# ホスト側からmysqlに繋ぐ
$ mysql -h 127.0.0.1 -P 4306 -uroot -p
```



