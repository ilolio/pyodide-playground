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

## 使用方法

1. 上部のコードエリアにPythonコードを入力
2. 「実行」ボタンをクリックまたはCtrl+Enterで実行
3. 実行結果が下部に表示

## 使用例
サンプルコード記入済みページは[こちら](https://ilolio.github.io/pyodide-playground/index_sample.html)

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