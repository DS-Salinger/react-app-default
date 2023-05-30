# コンテナ作成まで 

```
$ git clone git@github.com:DS-Salinger/react-app-default.git
$ cd react-app-default
$ mkdir app
$ docker compose build
```

#  TypeScript + React でプロジェクト作成

```
# Create project
$ docker compose run --rm react-app sh -c "npx create-react-app react-sample --template typescript"
```

# Webサーバの起動

```
$ docker compose up
```

でブラウザから http://localhost:3000/ にアクセスし
Reactのロゴが表示されることを確認する。
