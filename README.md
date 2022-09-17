# go-sandbox

## モジュールを作る

```console
mkdir hello
cd hello

go mod init example/hello
vi hello.go
go run .
```

## 外部パッケージを取り込む

Golang のソースコードでimportを宣言する。

```go
import "<prefix>/<package>""
```

`go mod` ツールでパッケージを取り込む。

```console
go mod tidy
```
