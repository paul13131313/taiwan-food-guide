# 台湾味覺散歩 — Taiwan Food Guide

台湾のおいしい店を紹介するWebサイト

## サイト構成

- `index.html` — メインページ（写真多めのエディトリアルデザイン）
- ダークモードベースのフォトマガジン風
- Bentoグリッド＋横スクロールカード＋エリアモザイク
- モバイル対応済み

## 公開方法（GitHub Pages）

```bash
# 1. リポジトリ作成
gh repo create taiwan-food-guide --public

# 2. ファイルをpush
git init
git add .
git commit -m "initial commit"
git branch -M main
git remote add origin https://github.com/paul13131313/taiwan-food-guide.git
git push -u origin main

# 3. GitHub Pages有効化
gh repo edit --enable-pages --pages-branch main
```

公開URL: https://paul13131313.github.io/taiwan-food-guide/

## 画像について

現在Unsplashのフリー写真を使用。実際の店舗写真に差し替え推奨。

## Claude Codeでの作業例

```bash
# 画像差し替え
claude "牛肉麺の画像URLをこれに変更して: https://example.com/photo.jpg"

# お店を追加
claude "横スクロールセクションに『永康牛肉麵』を追加して。TWD 280、台北・大安エリア"

# エリアページを追加
claude "台南のエリア詳細ページを新規作成して"
```
