# TypeScriptでChrome-extension

[TypeScriptで作るイマドキChrome拡張機能開発入門 - Qiita](https://qiita.com/markey/items/ea9ed18a1a243b39e06e)の写経

## ローカルで試す時

1. `yarn webpack`でdistの中身が生成される
1. Chromeで`chrome://extensions/`にアクセス
1. `パッケージ化されていない拡張機能を読み込む`からimport

## 注意
- `webpack/types`の`ConfigurationFactory`有無があるので`package.json`のバージョン指定は合わせること

## 記事になくて追加したもの

- manifest.json
- background.js

※上記に伴う設定なども追加
