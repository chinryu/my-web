# プロフィールサイト

このリポジトリは、静的な個人プロフィールページです。`index.html` と `styles.css` のみで構成されています。

## 使い方

1. 任意の静的ホスティングに配置するだけで公開できます（例: GitHub Pages, Netlify, Cloudflare Pages など）。
2. `index.html` 内の次の箇所をあなたの情報に置き換えてください。
   - タイトルと表示名: `あなたの名前`
   - 役割: `ソフトウェアエンジニア / Webエンジニア`
   - アバター画像 URL: `<img src="...">`
   - ソーシャルリンクの URL（GitHub, X, LinkedIn, メールなど）
   - 自己紹介テキスト、スキル、プロジェクトの内容

## ローカルで開く

エクスプローラーで `index.html` をダブルクリックするか、任意のローカル HTTP サーバーで配信してください。

PowerShell 例:

```powershell
Start-Process index.html
```

簡易サーバー例（Python ありの場合）:

```bash
python -m http.server 8080
```

## カスタマイズ

- カラーテーマやレイアウトは `styles.css` の CSS 変数やクラスを編集してください。
- 画像やアイコンを `img/` フォルダを作って配置し、`index.html` のパスを変更してください。

---

© あなたの名前


