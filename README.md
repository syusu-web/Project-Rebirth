# Project-Rebirth

**Project-Rebirth** は、「今までの自分と訣別し、新しい自分を創る」ことを目的とした  
自己改善・学習プロジェクトです。

## 📂 プロジェクト構成

Project-Rebirth/

├── README.md

├── study-log/

└── javascript30/


- `study-log/`  
  → 毎週の学習記録を Markdown 形式で保存します。

- `javascript30/`  
  → JavaScript30 の取り組み内容、メモ、成果物などをまとめます。

## 🎯 目的

- 学習習慣の定着  
- 小さな成功体験の積み重ね  
- 新しい自分になるための継続的な自己変革

## 🧭 運用ルール

- コミットメッセージは **英語（Conventional Commits）**
- ドキュメント類（README、study-logなど）は **日本語**
- 週単位で学習ログを追加
- 必ず「開始」「途中」「完了」など、何かしらの形で記録する

## 📝 ライセンス

本プロジェクトは個人学習用です。

## 📑 Conventional Commits（コミット規約）

本プロジェクトでは、履歴をわかりやすくするため  
**Conventional Commits** に基づいたコミットメッセージを使用します。

### 🔤 基本構造


### 🏷 type（種類）
| タイプ | 意味 | 用例 |
|--------|------|------|
| **feat** | 新機能の追加 | feat(study-log): add week1 log |
| **fix** | バグ修正 | fix: correct path for log file |
| **docs** | ドキュメント修正 | docs: update README |
| **style** | フォーマット修正（コードの意味は変えない） | style: format JS |
| **refactor** | リファクタリング | refactor: simplify function |
| **perf** | パフォーマンス改善 | perf: improve loop efficiency |
| **test** | テスト追加・修正 | test: add unit tests |
| **chore** | それ以外の雑多作業 | chore: update dependencies |

### 🗂 scope（対象）
任意。対象フォルダや範囲を書くとわかりやすい。

例：  
- `feat(study-log): ...`  
- `docs(readme): ...`  
- `chore(gitignore): ...`

### ✍ subject（要約）
- 50文字以内  
- 文末に「.」は付けない  
- 現在形で書く（Add, Update, Fix など）

---

# 📋 .gitignoreテンプレ  

```gitignore
# Node
node_modules/
npm-debug.log
yarn-debug.log
yarn-error.log

# Environment variables
.env
.env.local
.env.*.local

# Logs
logs/
*.log
*.tmp

# Editor settings
.vscode/
*.swp
.DS_Store

# Build directories
dist/
build/
out/

# OS files
Thumbs.db

# Project-specific ignores
# JavaScript30 の zip 展開フォルダなど
javascript30/00 - JavaScript30-master/

# Study logs backups
*.bak
