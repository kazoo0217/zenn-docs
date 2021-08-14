---
title: "はじめての zenn"
emoji: "😊"
type: "idea"
topics: ["markdown"]
published: false
---

## はじめての zenn

今日は `zen-cli` をインストールしてローカル環境を作成してみました

### ディレクトリを作る

任意のディレクトリに `zenn-docs` というディレクトリを作成

```sh
$ mkdir zenn-docs
```

### `zen-cli` をインストール

`zenn-docs` ディレクトリに移動して `zen-cli` をインストール

```sh
$ cd zenn-docs
$ npm init -y
$ npm i zenn-cli
```

### `zenn-docs` を初期化

`zenn-docs` ディレクトリ内に必要なファイル・ディレクトリが生成される

```sh
$ npx zenn init
```

### 新規記事作成

`zenn-docs/articles` ディレクトリ内に記事 `first-time-zenn.md` を作成する

```sh
$ npx zenn new:article --slug first-time-zenn
```

※ `--slug` は 12 文字以上 50 以下で指定する

### ブラウザーで表示とオートリロード

`localhost:8000` にアクセスしてブラウザに表示します  
`first-time-zenn.md` を編集・保存すると表示が更新されます

```sh
$ npx zenn preview
```

## まとめ

そんなところです
