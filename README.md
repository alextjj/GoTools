# GoTools

保存  goTools 

安装goimports：
$ mkdir -p $GOPATH/src/golang.org/x
$ cd $GOPATH/src/golang.org/x
$ git clone https://github.com/golang/tools.git
$ go install golang.org/x/tools/cmd/goimports 

$ goimports -w hello.go

可以 将安装后的文件  $GOPATH/bin copy 到 $GOROOT/bin 这样每个object就能公用

全文地址请点击：https://blog.csdn.net/pujiao5201314/article/details/72903062?utm_source=copy 
