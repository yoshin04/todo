# todo

## 環境構築
```
cp .env.example .env
docker compose up
GO_ENV=dev go run main.go
```

## 開発環境マイグレーション
```
GO_ENV=dev go run migrate/migrate.go
```
