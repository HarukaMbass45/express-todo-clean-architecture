# express-todo-clean-architecture
クリーンアーキテクチャでTODOのAPIサーバーを作成する

## environment
- node.js lts
- prisma を入れる予定

## how to build
1. docker compose で環境を立ち上げる
```
$ docker compose up -d
```

2. APIディレクトリに移動してもろもろやる
```
// 作業ディレクトリに移動
$ cd api

// マイグレーションを実行する
$ docker compose exec api yarn db:migrate
```
3. コンテナ内ですでに dev サーバーが動いているので検証できる
    デフォルトは port 3333にしてる
