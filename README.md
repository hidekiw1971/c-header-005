画像をコピペ

# compornent（共通部品）
- component（ヘッダー、ボタン、ドロワーメニュー設置）

# w3c html/css ck
- confirmed

# browser ck
- chrome ok
- safari ok
- firefox ok
- edge ok

# note
- 'reset.css'で'body'に'height 100vh'を持たせてたのでコメント。→ mobile実機で見ると表示崩れした為。
- '.js-drawer-menu'に'height 100vh'を持たせてたが削除。→ mobile実機で見ると表示崩れした為。
- 上記では結果ダメ。'height: 100dvh;'で全て解決した。

## portfolio url:

- https://c-0126.wtb.cfbx.jp/

## codepen url:
- 

## reference site:
- https://coliss.com/articles/build-websites/operation/css/css-fix-for-100vh-in-ios.html
- https://c-limber.co.jp/blog/3131
- https://zenn.dev/futa/articles/90d7410650a73e

## 更新履歴

- 2023/2/26 初版 対応中
- 2023/3/1  mobile(safari,chrome)での100vh不具合対応。→ 100dvhに変更

## 環境起動手順
- term起動
- cd 対象ディレクトリへ移動
- npm i
- npx gulp
- 起動完了
