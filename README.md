# gvm

Go 语言版本管理器; 

forked from [Moovweb](https://www.moovweb.com)

替换了代码下载源以及版本获取源，方便中国开发者使用，使用方式不变～

## 安装 Gvm
To install:

    bash < <(curl -s -S -L https://raw.githubusercontent.com/mosaic101/gvm/master/binscripts/gvm-installer)

如果正在使用 zsh， 就用 zsh 替代 bash


## Go 版本列表
目前已安装的 Go 版本:

    gvm list

可供下载的 Go 版本列表:

    gvm listall

## Go 安装
    gvm install go1.4
    gvm use go1.4 [--default]
    
当 Go 被使用时， $GOROOT 跟 $GOPATH 会自动配置

## Go 版本大于 1.4 安装方式

    gvm install go1.4 -B
    gvm use go1.4
    export GOROOT_BOOTSTRAP=$GOROOT
    gvm install go1.9.4

