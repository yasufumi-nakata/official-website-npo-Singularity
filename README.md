# official-website

NPO Singularity公式サイトのリポジトリです。GitHub Pages でホスティングできるよう、`docs/` 以下に静的ファイルを配置しています。

## ディレクトリ構成
- `docs/index.html` — 1ページ構成の本体。手元のブラウザで開くだけで確認できます。
- `docs/assets/` — スタイルとスクリプト。配色や余白などは `styles.css` にまとまっています。
- `docs/site-blueprint.md` — 要件・情報設計メモ。コンテンツ更新時の参照用。

## 更新と公開の流れ
1. 文言やリンクを修正する場合は `docs/index.html`（または `docs/assets/styles.css`）を直接編集します。
2. 変更をコミットして GitHub に push したら、Pages の公開先を `main` ブランチ / `docs` ディレクトリに設定してください。
3. 数分後に `https://npo-singularity.github.io/official-website/` で反映を確認できます。

追加のアイデアや素材があれば Issue や Discord で共有してもらえると助かります。
