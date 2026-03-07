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

- ブランチ名: `feat-{issue番号}` （例: `feat-79`）
- PR ラベルによるセマンティックバージョニング:
  - `major`: 新しい職場の追加
  - `minor`: 既存の職場でのプロジェクトの追加
  - `patch`: 既存のプロジェクトの詳細の変更や追記（デフォルト）
- release-drafter によるリリース自動生成

## Lint ルール（注意点）

- 全角文字と半角文字の間にはスペースを入れる（例: `Spring Boot を使用した` → OK、`Spring Bootを使用した` → NG）
- pre-commit フックで textlint と markdownlint-cli2 が自動実行される
- textlint は `docs/README.md` のみが対象

## 編集時の注意

- `docs/README.md` を編集した場合は、必ず `docs/en/README.md` にも同じ内容を英語で反映すること
- 顧客名など機密性のある情報は適度に曖昧にする（例: 「大手インフラ企業」）
