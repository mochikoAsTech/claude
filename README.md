# claude

Claude Code用のMCPサーバー実験リポジトリです。

## 構造

```
claude/
├── mcp-examples/          # 各MCPサーバーのサンプル
│   ├── line-bot/         # LINE Bot MCP Server
│   │   ├── .env         # 環境変数（gitignore済み）
│   │   ├── README.md    # セットアップと使用方法
│   │   └── test-scripts/ # テストスクリプト
│   └── ...              # 他のMCPサーバー
├── .mcp.json            # MCPサーバー設定
├── .gitignore           # Git除外設定
├── CLAUDE.md            # Claude Code用ガイド
└── README.md            # このファイル
```

## 使用方法

1. リポジトリをクローン
2. 各MCPサーバーのディレクトリにある`README.md`を参照
3. 必要な環境変数を`.env`ファイルに設定
4. Claude Codeでプロジェクトを開く

## 利用可能なMCPサーバー

- **LINE Bot MCP Server** - LINE Messaging APIとの連携
  - メッセージ送信、ユーザー管理、リッチメニュー管理など

## セキュリティ

- `.env`ファイルはGitで管理されません
- アクセストークンなどの機密情報は環境変数で管理してください
