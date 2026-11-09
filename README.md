# S.K. Studio アプリのサポートサイト

S.K. Studio のアプリのサポートページ（プライバシーポリシー・利用規約・お問い合わせ）を、GitHub Pages で公開するためのリポジトリです。

公開URL: https://s-k-studio-apps-9.github.io/

## 構成

```
index.html          … トップ（アプリ一覧）
assets/style.css    … 全ページ共通のスタイル
aiko/               … あいこ（Aiko）
  index.html        … サポート（よくある質問・お問い合わせ）
  privacy.html      … プライバシーポリシー
  terms.html        … 利用規約
  icon.png          … アプリアイコン（256px）
taskpnk/            … Taskpnk（英語・日本語の併記）
  index.html / privacy.html / terms.html / icon.png
  theme.css         … Taskpnk 用のダーク配色（共通 style.css の後に読み込む）
```

## 新しいアプリを追加するとき

1. `aiko/` をコピーして、アプリ用のフォルダ（例: `newapp/`）を作る
2. 各ページの文章とアイコンを、新しいアプリの内容に書き換える
3. トップの `index.html` のアプリ一覧に1項目追加する
4. コミットして `main` にプッシュすると、数分で公開されます

App Store Connect に登録するURLの例:
- プライバシーポリシー: `https://s-k-studio-apps-9.github.io/<フォルダ名>/privacy.html`
- サポートURL: `https://s-k-studio-apps-9.github.io/<フォルダ名>/`
