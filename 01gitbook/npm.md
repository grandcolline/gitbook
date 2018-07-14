# npmで管理

## package.json

```
{
  "name": "GitbookDemo",
  "scripts": {
    "serve": "gitbook install ; gitbook serve",
    "build": "gitbook install ; gitbook build",
    "deploy": "gh-pages -d _book"
  },
  "dependencies": {
    "gh-pages": "^1.2.0",
    "gitbook-cli": "^2.3.2"
  }
}
```

## 使い方

### install

```
$ npm install
```

初回およびモジュールの変更時のみでいいと思う

### ローカルでサーバ起動

```
$ npm run serve
```

### ビルド

```
$ npm run build
```

`_book`に成果物ができる

### デプロイ（gh-pagesに）

```
$ npm run deploy
```

`_book`をgh-pagesブランチにpushする


