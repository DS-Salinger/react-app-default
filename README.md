# コンテナ作成まで 

```
$ git clone git@github.com:DS-Salinger/react-app-default.git
$ cd react-app-default
$ mkdir app
$ docker compose build
```

# Next.js + React のインストール

```
# Install Next.js 
$ docker compose run --rm react-app npm install create-next-app

# Create project
$ docker-compose run --rm react-app npx create-next-app sample_app --ts
```

# Webサーバの起動

```
$ docker compose up
```

でブラウザから http://localhost:3000/ にアクセスし
Reactのロゴが表示されることを確認する。
