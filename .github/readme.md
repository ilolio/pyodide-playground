# ブラウザでPythonを実行するWebページ

ブラウザ上でPythonコードを記述・実行できるWebアプリケーションです。WebAssembly技術を活用したPyodideにより、サーバーサイドを必要とせずにクライアントサイドでPythonコードを実行します。

## 試す
[GitHub Pages](https://ilolio.github.io/pyodide-playground/)

## 特徴

* ブラウザ上で完結するPython実行環境
* 高機能なコードエディタ（シンタックスハイライト、自動インデント）
* `micropip` を使用した追加パッケージのインストール（pandas, numpy など）
* Ctrl+Enter でのクイック実行
* 実行結果のリアルタイム表示
* URLパラメータでPythonコードを共有

## 使用方法

1. 上部のコードエリアにPythonコードを入力
2. 「実行」ボタンをクリックまたはCtrl+Enterで実行
3. 実行結果が下部に表示

## 使用例
サンプルコード記入済みページは[こちら](https://ilolio.github.io/pyodide-playground/index.html?code=H4sIAAAAAAAAA22RQWvUQBTH7_MphvXQLISgeCvkJoLgydOCSBgyk2UwyYSZWXAVwWSgbvFSCuLBUqhKW2mrpSJst1o_zGx2_RjOTJptqoZAMm_e_73f_z2aFYxLWKAcIwHNW2CQcJZB8TQliOcBRhIJIgWkTWbKEI4op-JmWsYwSSNBUhJLyvI2W3JE80gSISNRpFTeFKU0N9_IaVvFQzakQtL4ERlyIoSpBcAt-MA01Oq1Vj909UtXF1oprSa62tbqxAbVJrBMMLzm8_oAJyZQ4OCe8XCfo4x49sJZ8mHM0lGWi9CFEoLkiJMoN0nCCh-vScSHRK49MSVcSnO2MB2QbUuhjh3CG62-6er0mq481GpDV-eOdBU8qicb9eYZGERuOD4cuPn4cNwGxi5g-v49PQ9A8-AkwJwVXkvoQ_SMivBO34ddbh82QvqchLeDuz7kZscsi4RE0kRAv7FyoqupYzSkHy1j9bV-v1tPT7X64IweGZfznzuLyZYu3-lX5b-OQbPA8D-7M0twl0Fi6Acdg_bniqAd0Wqq5cF8NllMj8E4KjjBpnBTwx5o7OoYZ07dJC6_by12dwzn773D5acZKDjNpdfrXq73bFtb4apra678sjy7rGf7Vv357fxyD6A4HnEUj1d9Rcw48Tprct2bJkmvka_DF63uZa8P_gDfUvKiVwMAAA&packages=H4sIAAAAAAAAAytIzEtJLNYpTs7MzizRzUlNLMoDABQjWpoTAAAA)

## 動作環境

* モダンなWebブラウザ（Chrome, Firefox, Safari, Edge など）
* JavaScript有効化が必要
* インターネット接続（初回ロードおよびパッケージインストール時）

## 使用技術

* [Pyodide](https://github.com/pyodide/pyodide) - WebAssembly/Emscriptenを利用したPython実行環境
* [ACE Editor](https://ace.c9.io/) - 高機能なWebベースコードエディタ

## 制限事項・注意点

* ブラウザベースの実行環境であるため、以下の制限があります：
  - ローカルファイルへのアクセスは制限されます
  - 一部のPythonパッケージは利用できない場合があります
* 初回ロード時は環境のダウンロードが必要なため、時間がかかる場合があります
* パッケージのインストールにはインターネット接続が必要です


## ライセンス

MITライセンス