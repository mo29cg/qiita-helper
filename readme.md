# qiita-helper Chrome Addon

## 概要

エンジニアに関する知識を記録・共有するためのサービス「Qiita」を NVDA で閲覧する際、見出しとともに不要な読み上げがなされてしまう問題を暫定的に修正します。

## やっていること

本件の原因は、見出しの中にあるページ内リンク生成用の a タグ内に読み上げられるテキストがないことらしいです。
こちらは yamahubuki 様のフォークプロジェクトですが、h1 等のタグの中に a タグがる状態から、a タグで h1 タグ等を囲ううように構造を変えるアプローチで解決しています。

## ご利用方法

1. 本リポジトリをクローン、もしくはダウンロードしてから展開して、どこかに配置
1. Chrome ブラウザで、[chrome://extensions](chrome://extensions)にアクセス
1. 画面右上から、開発者モードを ON
1. 「パッケージ化されていない拡張機能を読み込む」より、本アドオンの場所(ディレクトリ)を指定

## ライセンス

- MIT
