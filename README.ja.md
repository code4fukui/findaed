# findaed (AEDナビ)

デバイスのGPSを使用して日本国内の近くにあるAED（自動体外式除細動器）の設置場所を特定し、Googleマップ上に表示するオープンソースのWebアプリケーションです。

## デモ

[**ライブデモ**](https://code4fukui.github.io/findaed/)

## 機能

- デバイスのGPSを使用して最寄りのAED設置場所を自動的に特定します。
- インタラクティブなGoogleマップ上に施設の場所を表示します。
- 日本語、英語、中国語、韓国語などの多言語に対応しています。
- 緊急避難所や医療機関、公衆トイレなど、他の公共施設のデータ定義も含まれています。

## ローカル開発環境のセットアップ

このプロジェクトをローカルで実行するには、GoogleマップのAPIキーが必要です。

1. [Google APIs Console](https://console.developers.google.com/projectselector/apis/credentials) からGoogleマップのAPIキーを取得します。
2. `lib/gmap.js` ファイル内のプレースホルダー `API_KEY` の値を、取得した自身のキーに置き換えます。
3. `index.html` ファイルをWebブラウザで開きます。

## データソース

このアプリケーションは、日本の[オープンデータポータル (ODP) のSPARQLエンドポイント](https://sparql.odp.jig.jp/data/sparql)から施設データを取得します。

## 謝辞

このプロジェクトは、Taisuke Fukunoによる `fukuno.js` ユーティリティライブラリ (CC BY) を利用しています。

## ライセンス

[MIT](LICENSE)
