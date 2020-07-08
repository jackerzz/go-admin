# gin-admin
- 一个用基于gin写的后台项目
- 一个基础的架构系统
# 环境搭建（win10）
```
    安装：
        下载地
            https://studygolang.com/dl
        当前使用的：
            https://studygolang.com/dl/golang/go1.12.7.windows-amd64.zip
    环境变量配置
        用户级：
            GOPROXY=https://mirrors.aliyun.com/goproxy/
            BIN=C:\go\bin
        系统级
            GOPATH=F:\Workspace
            GOROOT=C:\go
            path=C:\go\bin
```
# 使用的是go mod
```
    修改mysql 的 root password
    拉取go.mod中的依赖
        go build
    打包运行：
        go build
        ./gin-admin.exe
```