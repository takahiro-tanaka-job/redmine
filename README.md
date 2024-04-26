# README

Docker社のオフィシャルイメージのredmineを使用する  
 `https://hub.docker.com/search?q=redmine`

オフィシャルイメージに移動し、ページの中間あたりに ”How to use this image” というものがあるので見てみると、Docker Composeのためのサンプルが用意されているので、これをもとにdocker-compose.yml を作成していきます。


### コンテナ起動  
`$docker-compose up -d`

###  起動確認  
`$docker-compose ps`

### アクセス  
`http://localhost:8080/`
+ ログインID : admin
+ パスワード : admin


## 参考
1. Dockerを使ってEC2にredmineを構築する(前編)  
https://www.geekfeed.co.jp/geekblog/docker-redmine