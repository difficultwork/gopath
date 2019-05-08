# gopath
gopath搭配vscode打造golang开发环境

## 下载代码
 ```
 git clone --recursive https://github.com/DifficultWork/gopath.git
 ```

并将根目录设置为环境变量GOPATH的value
注意：只能使用git clone --recursive下载，其他方式无法下载引用的代码库！

## 安装工具
 ```
 cd %GOPATH%/src
 go install github.com/nsf/gocode
 go install github.com/uudashr/gopkgs
 go install github.com/rogpeppe/godef
 go install github.com/lukehoban/go-outline
 go install github.com/newhook/go-symbols
 go install golang.org/x/tools/cmd/guru
 go install golang.org/x/tools/cmd/gorename
 go install github.com/josharian/impl
 go install github.com/sqs/goreturns
 go install github.com/bytbox/golint
 go install github.com/cweill/gotests
 go install github.com/go-delve/delve/cmd/dlv
 ```
