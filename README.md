# main-bower-files is nice

Qiitaに投稿した記事[bowerをうまく使う](http://qiita.com/endaaman/items/65f4df9b43e29d7544d1)のサンプルです。

## 準備
```
npm install
bower install
```

## ビルド
### 開発用ビルド(bower_componentsのままインジェクト)
```
gulp
```
or
```
gulp build
```

### プロダクションビルド(bower_componentsの中身が結合されてインジェクトされる)
```
gulp prod build
```


## テスト
```
npm test
```


## 実際に起動する
静的サーバーはgulpの方に書いてないので頑張って起動してください。
publicに入って
```
python -m SimpleHTTPServer
```
とかが楽かな？

