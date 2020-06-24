# Go语法树入门

Go语法树是Go语言源文件的另一种语义等价的表现形式。而Go语言自带的`go fmt`和`go doc`等命令都是在Go语法树的基础之上分析工具。因此将Go语言程序作为输入数据，让我们语法树这个维度重新审视Go语言程序，我们将得到创建Go语言本身的技术。Go语法树由标准库的`go/ast`包定义，它是在`go/token`包定义的词法基础只是抽象的语法树结构。本书简单介绍语法树相关包的使用。

![](cover.png)

- 作者：柴树杉，Github [@chai2010](https://github.com/chai2010)，Twitter [@chaishushan](https://twitter.com/chaishushan)
- 作者：史斌，Github [@benshi001](https://github.com/benshi001)
- 作者：丁尔男，Github [@3dgen](https://github.com/benshi001)
- 主页：https://github.com/chai2010/go-ast-book


# 版权

版权 [柴树杉](https://github.com/chai2010)、[史斌](https://github.com/benshi001)和[丁尔男](https://github.com/3dgen)，保留相关权力。为了保护读者的权益，我们和出版社沟通为读者争取到以下权利：

1. Github平台免费在线阅读。
1. 关注本书项目(Star)，同时关注任意一个作者的 Github 或 推特账号，自动获得下载的权利。
1. 通过 [微信](images/donate-weixin-github-chai2010-20yuan.jpg) 或 [支付宝](images/donate-alipay-github-chai2010-20yuan.jpg) 二维码支付 20元 获得 下载的权利。

**禁止非 Github 平台转载，作者保留相关法律权力。**

