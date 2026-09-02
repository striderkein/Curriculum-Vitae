# Curriculum-Vitae

職務経歴書リポジトリ。日本語版（`docs/README.md`）と英語版（`docs/en/README.md`）の両方を管理する。

## プロジェクト構成

- `docs/README.md` — 職務経歴書（日本語）
- `docs/en/README.md` — 職務経歴書（英語）
- `README.md` — リポジトリ説明（GitHub 用）
- `pdf-configs/` — PDF 変換設定
- `.textlintrc` — textlint ルール設定
- `.markdownlint-cli2.jsonc` — markdownlint 設定

## コマンド

- `npm run lint` — docs/README.md の textlint チェック
- `npm run build:pdf` — 日本語版 PDF 生成
- `npm run build:pdf-en` — 英語版 PDF 生成

## ブランチ・PR ルール

- ブランチ名は変更の種類で決める。リリースノートのカテゴリは、このブランチ名から autolabeler が自動で決定する
  - `feat-{issue番号}` — 職歴・プロジェクトの追加や追記（例: `feat-79`）→ `feature`
  - `fix-{issue番号}` — 不具合修正（例: `fix-92`）→ `bug`
  - `chore-{issue番号}` — CI・設定・依存関係などの保守 → `chore`
  - `docs-{issue番号}` — リポジトリ説明など職務経歴書本体以外の文書 → `documentation`
- 手動で付けるラベルは `major` / `minor` / `patch` の 3 つだけにする
  - `major`: 新しい職場の追加
  - `minor`: 既存の職場でのプロジェクトの追加
  - `patch`: 既存のプロジェクトの詳細の変更や追記（デフォルト）
- カテゴリラベル（`feature` / `bug` / `chore` / `documentation` / `refactor` / `enhancement`）は手動で付けない
  - release-drafter はマッチしたカテゴリすべてに PR を掲載するため、複数付けると同じ PR がリリースノートに重複して並ぶ（Issue #92）
- release-drafter によるリリース自動生成
  - draft が作られるだけなので、公開は手動で行う（`gh release edit vX.Y.Z --draft=false --latest`）
  - 公開すると `build pdf` ワークフローが走り、PDF がリリース資産に添付される

## Lint ルール（注意点）

- 全角文字と半角文字の間にはスペースを入れる（例: `Spring Boot を使用した` → OK、`Spring Bootを使用した` → NG）
- pre-commit フックで textlint と markdownlint-cli2 が自動実行される
- textlint は `docs/README.md` のみが対象

## 編集時の注意

- `docs/README.md` を編集した場合は、必ず `docs/en/README.md` にも同じ内容を英語で反映すること
- 顧客名など機密性のある情報は適度に曖昧にする（例: 「大手インフラ企業」）
