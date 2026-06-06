# AGENTS.md

このリポジトリは GitHub Pages 公開専用である。

## 公開ルール

- public リポジトリに置いたファイルは、HTML からリンクしていなくても公開済みとみなす。
- 公開対象は allowlist 方式で管理する。
- 許可ファイル以外を追加してはいけない。
- PDF、名刺画像、計画書 HTML、print_exports、メール文、実メールアドレス、電話番号、病院名を含む内部資料、作業ログ、元データ、個人情報を含む画像や文書は絶対に含めない。

## 許可ファイル

- `.gitignore`
- `AGENTS.md`
- `midwife-ai-business-card-lp/index.html`
- `midwife-ai-business-card-lp/lp.html`
- `midwife-ai-business-card-lp/assets/lp-qr-code.png`
- `midwife-ai-business-card-lp/assets/lp-qr-code.svg`
- `midwife-ai-business-card-lp/assets/newborn-lp-hero-gpt-image-2.png`

## 作業前確認

push 前に必ず以下を表示し、ユーザーの承認を待つ。

- `git status`
- `git diff --stat`
- `git ls-files`
- 公開対象ファイル一覧
- 禁止語検索結果。禁止語検索は、公開本文・公開 HTML・公開対象ファイル名・公開リンクを対象とする。ただし、`.gitignore` と `AGENTS.md` は管理ルールファイルのため禁止語検索から除外する。ルール説明として含まれる禁止語は検出対象外とする。

## 承認必須操作

公開、push、Pages 有効化、削除、履歴変更は必ずユーザーの承認を待つ。
