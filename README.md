# Git Flow
main │ ├─── hotfix/urgent-fix │ ↳ main + develop へマージ │ develop │ ├─── release/1.2.0 │ ↳ main + develop へマージ │ ├─── feature/user-auth │ ↳ develop へマージ │ └─── bugfix/fix-profile-issue ↳ develop へマージ

## 🔧 セットアップ手順

### 前提

- Ruby (例：3.2.2)
- Rails (例：7.1.0)
- Node.js & Yarn
- Docker（任意）

### ローカル環境構築（Dockerを使う場合）

```bash
git clone https://github.com/your-name/your-app.git
cd your-app

# 環境変数のコピー
cp .env.example .env

# Dockerで立ち上げ
docker-compose up --build