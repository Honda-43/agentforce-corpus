# agentforce-corpus — 統制コーパス（架空企業60社）

Agentforce×Claude 検証ラボの統制コーパス。掲載企業はすべて架空。

## 公開手順（GitHub Pages）
1. GitHubに `agentforce-corpus` リポジトリを作成（Public。Pagesは無料枠でPublicが必要）
2. このフォルダの中身をリポジトリ直下にpush
3. Settings > Pages > Source を「Deploy from a branch」/ main / `/ (root)` に設定
4. 数分後 `https://<org>.github.io/agentforce-corpus/corpus/v1/index.html` で確認
5. 確認後、タグ `corpus-v1` を打って凍結。以後 v1 配下は変更しない（修正は v2 として別ディレクトリ）

## 注意
- 全ページ `<meta name="robots" content="noindex,nofollow">` ＋ `robots.txt` で全拒否
- フッターに架空である旨を明記
- `corpus/v1/VERSION.json` の `frozen` を公開後 true に変更してコミット
