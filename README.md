# Go-Tutorial

参考サイト: http://gihyo.jp/dev/feature/01/go_4beginners

## 環境構築
```
$ brew install go
```

## 実行とビルド
実行
```
$ go run hello.go
```

build
```
# 通常ファイルの場合
$ go build hello.go
# プロジェクトの場合
$ echo $GOPATH
$ echo $GOPATH
/Go-Tutorial/myproject
$ cd $GOPATH/src/main
$ go install
```
