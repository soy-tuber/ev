# ev

EVデータベース — 日本で販売中／発売予定のEVを一覧・絞り込み・ソートできる静的サイトです。

## 公開（GitHub Pages）

`index.html` をリポジトリ直下に配置しています。GitHub Pages を「ブランチから公開」で
有効にすると、そのまま公開されます。

1. GitHub の **Settings → Pages** を開く
2. **Build and deployment → Source** を **Deploy from a branch** にする
3. Branch を **`main`** の **`/ (root)`** に設定して **Save**
4. 数分後、以下のURLで閲覧できます: **https://soy-tuber.github.io/ev/**

`.nojekyll` を置いてあるので、Jekyll 処理されず HTML がそのまま配信されます。

## ローカルでの確認

```sh
python3 -m http.server
# http://localhost:8000 をブラウザで開く
```
