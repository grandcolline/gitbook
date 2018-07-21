# circleCIでデプロイ

circleCIで、
```
npm run build
npm run deploy
```
を実行する。

* [config.yml](https://github.com/grandcolline/gitbook/blob/master/.circleci/config.yml)

上記の設定ファイルでは、`gh-pages` 以外のブランチで、ビルドを実施。ビルド成功後に `master` ブランチの場合のみデプロイをする。

