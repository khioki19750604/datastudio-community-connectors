# Qiita Connector

Qiitaに接続するためのコネクタのサンプルです。

自分が投稿した投稿データおよび投稿についた いいね データを取得することができます。

詳しくはQiitaの記事をご覧ください。

https://qiita.com/prograti/items/52eea1909afd7a5869c9

## 注意事項

全ての投稿データをフェッチし、さらに各投稿に対して全ての いいね データをフェッチします。

投稿数が多い方が利用するとAPIのコール回数が非常に多くなりますのでご注意ください。

（QiitaのAPI制限は認証済みユーザーで1時間に1000回です）

## ライセンス

MIT
