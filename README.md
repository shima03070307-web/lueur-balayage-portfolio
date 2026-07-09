# Lueur BALAYAGE GitHub Pages 公開用

このフォルダを GitHub Pages の公開元として使います。

## 公開するファイル

- `index.html`: 架空美容室サイト
- `case-study.html`: 制作事例ページ
- `styles.css`
- `script.js`
- `assets/`: 公開に必要な軽量画像だけ
- `.nojekyll`: GitHub Pagesで静的ファイルをそのまま配信するためのファイル
- `robots.txt`
- `404.html`

## GitHub Pagesで公開する手順

1. GitHubで新しいリポジトリを作る。
2. この `github-pages` フォルダの中身を、リポジトリ直下へアップする。
3. GitHubの `Settings` -> `Pages` を開く。
4. `Build and deployment` の `Source` を `Deploy from a branch` にする。
5. `Branch` を `main`、フォルダを `/root` にして保存する。
6. 数分待って、表示されたURLを開く。

## 公開URLが決まったら確認すること

- `case-study.html` を制作事例として検索に出したい場合は、canonical、`og:url`、`sitemap.xml` を公開URLに合わせて追加する。
- `index.html` は架空美容室サイトなので、誤認防止のため `noindex,follow` のままにしている。
- 実際の問い合わせ先が決まったら、制作事例ページのCTAを差し替える。
- 独自ドメインを使う場合は、GitHub Pages設定後に `CNAME` を追加する。

## 注意

このサイトは架空制作例です。実在する店舗、住所、電話番号、料金、予約URLではありません。
