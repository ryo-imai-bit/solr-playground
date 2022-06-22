# solr-playground

改訂第三版 Apache-Solr入門、ほか

## config

https://github.com/docker-solr/docker-solr#single-server-with-docker-compose から

### サンプル投入

``` zsh

docker compose exec -it solr post -c gettingstarted example/exampledocs/manufacturers.xml

```

## 改訂第三版 Apache-Solr入門、ほか

[サンプルデータ](https://github.com/solrbook3/examples)

### 2章

``` bash

solr create_Core -c solrbook -d basic_configs

```

### 3章

サンプルデータの投入

``` bash

post -c solrbook /var/solr/solrbook/sample-books.json

```
