# laravel_dev

## docker環境構成

```
(第一階層の構成)
.
├── .git
├── .gitignore
├── README.md
├── app_src
├── docker
└── server

```

ディレクトリ名|内容|備考
-|-|-
app_src|アプリケーションのソース格納場所|永続化と別でリポジトリ化
docker|docker設定の格納場所|build時に設定するミドルのファイルもこちらに置く
server|永続化するミドル系やDBデータの置き場所|永続化
