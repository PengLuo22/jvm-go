# jvm-go
用 golang 实现一个 JVM





## 任务1：编写一个类似 java 的命令行工具，用它来启动我们自己的虚拟机。



开发环境

| 名称 | 版本   | 备注               |
| ---- | ------ | ------------------ |
| JDK  | 11     |                    |
| GO   | 1.22.3 | https://go.dev/dl/ |
|      |        |                    |



在 src\ch01 目录下执行

```go
go mod init ch01

go mod tidy

go run main.go cmd.go
```

进入： C:\Users\Administrator\go\bin，可以看到ch1.exe
执行 ch01.exe -help




