# ev

EVデータベース — 日本で販売中／発売予定のEVを一覧・絞り込み・ソートできる静的サイトです。

## 公開（GitHub Pages）

`main` ブランチへの push をトリガーに、GitHub Actions が自動で GitHub Pages を
有効化してデプロイします（`.github/workflows/pages.yml`）。スマホからでも
Settings の手動操作は不要です。

- 公開URL: **https://soy-tuber.github.io/ev/**
- デプロイ状況: リポジトリの **Actions** タブで確認できます

`index.html` をリポジトリ直下に配置し、`.nojekyll` で Jekyll 処理を無効化しています。

## ローカルでの確認

```sh
python3 -m http.server
# http://localhost:8000 をブラウザで開く
```
