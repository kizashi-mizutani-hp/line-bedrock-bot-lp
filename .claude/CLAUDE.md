# Kagami.AI LP プロジェクト設定

## 許可されるコマンド・操作

### ✅ 許可 - ファイル操作
- ファイルの作成 (Write)
- ファイルの読み取り (Read)
- ファイルの編集 (Edit, MultiEdit)
- ディレクトリの作成 (mkdir)
- ファイル・ディレクトリのコピー (cp)
- ファイル・ディレクトリの移動・リネーム (mv)

### ✅ 許可 - 情報取得系コマンド
- ファイル一覧表示 (ls, LS)
- ファイル検索 (Glob, Grep)
- Git状態確認 (git status, git log, git diff)
- ブラウザでファイルを開く (open)

### ✅ 許可 - その他
- TodoWrite (タスク管理)
- WebFetch (情報取得)

### ❌ 禁止 - Git操作
- git commit
- git push
- git pull
- その他のリモートとの同期操作

### ❌ 禁止 - システム影響操作
- ファイル・ディレクトリの削除 (rm)
- システム設定変更
- 外部サービスへのデプロイ

## プロジェクト方針

- 変更は手動でcommit/pushする
- セキュリティを重視した開発
- シンプルで保守しやすいコード
- レスポンシブデザイン対応必須

## 技術スタック

- HTML5 + CSS3
- 静的サイト (GitHub Pages)
- セキュリティヘッダー実装
- Google Fonts (Noto Sans JP)