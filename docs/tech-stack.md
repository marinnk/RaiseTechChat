# 使用技術

姉妹プロジェクト[RaiseTechSNS](../../RaiseTechSNS)と同一の技術スタックを基本とし、チャットのリアルタイム通信のためにWebSocketを追加しています。

| 領域 | 技術 |
| --- | --- |
| バックエンド | Java 25 / Spring Boot 4.1 / MyBatis / Gradle |
| フロントエンド | TypeScript / React 19 / Vite |
| データベース | PostgreSQL 16（Flywayでマイグレーション） |
| 認証 | Spring Security + JWT（アクセストークン＋リフレッシュトークン方式） |
| リアルタイム通信 | Spring WebSocket + STOMP |
| ファイル保存 | Amazon S3（ローカル開発ではMinIO） |
| メール送信 | Spring Boot Mail（ローカル開発ではMailpit） |
| API仕様書 | Swagger UI / OpenAPI（springdoc-openapi） |
| テスト | Vitest / Testing Library / Playwright |
| ローカル環境 | Docker Compose |
