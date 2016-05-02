
# 概要

docker-composeを使って  
OSX上でsitespeed.io/graphite/grafanaで  
sitespeed.ioのメトリックスをグラフ化する環境を構築してみる。

# 準備

docker-toolboxをインストール  
https://www.docker.com/products/docker-toolbox

# 構築手順

## 編集
[local] vi docker-compose.yml

## 構築
```
[local] docker-compose up
[local] docker-compose up -d
```

## 確認

### graphite
http://192.168.99.100:8080
guest/guest

### grafana
http://192.168.99.100:3000

## 計測

## 停止
```
[local] docker-compose stop
```

## 停止
```
[local] docker-compose rm
```

# 参考

http://blog.takanabe.tokyo/2015/11/30/1667/
