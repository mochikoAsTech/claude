# LINE Bot MCP Server Example

LINE Bot MCP Serverを使ったサンプル実装です。

## セットアップ

1. LINE Developers ConsoleでMessaging APIチャネルを作成
2. Channel Access Tokenを取得
3. `.env`ファイルを作成し、トークンを設定：
   ```
   LINE_CHANNEL_ACCESS_TOKEN=your_token_here
   ```

## 使用方法

Claude Codeでこのプロジェクトを開くと、自動的にLINE Bot MCPサーバーが利用可能になります。

## 主な機能

- テキストメッセージの送信
- フレックスメッセージの送信
- ユーザープロフィールの取得
- 一斉配信
- リッチメニューの管理

## テストスクリプト

`test-scripts/`ディレクトリに各種テストスクリプトがあります。

## 参考資料

- [LINE Bot MCP Server](https://github.com/line/line-bot-mcp-server)
- [LINE Messaging API](https://developers.line.biz/ja/docs/messaging-api/)