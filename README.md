# HTTP缓存反向代理

Go1.27.1与Chi5.2.1基础项目。Chi依赖已放入vendor，可直接构建。
当前仅包含HTTP启动入口和/healthz，尚未实现代理与缓存业务。

```sh
go build -o bin/server ./cmd/server
go test ./...
go run ./cmd/server
```

LISTEN_ADDR指定监听地址，默认127.0.0.1:8080。
