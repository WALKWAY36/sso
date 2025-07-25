## RUN app

```bash
go run .\cmd\sso\main.go --config=./config/local.yaml
```

## RUN migrator

```bash
go run .\cmd\migrator --storage-path=.\storage\sso.db --migrations-path=.\migrations
```
