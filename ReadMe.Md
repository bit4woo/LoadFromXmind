### about

个人习惯使用mindmap来记录和梳理知识点或者一些工具脚本。而且发现每次到一个新的环境，总是需要一个个得去从github上下载这些脚本。

为求方便，有了该脚本。

**根据xmind中的记录，自动从github上clone，或者pull 一些常用的脚本。**



### requirement

1. 安装xmind-sdk-python

`git clone https://github.com/xmindltd/xmind-sdk-python.git`

`cd xmind-sdk-python`

`setup.py install`

2. 需要系统上安装了git，并且加入到了环境变量中，即需要在命令行下直接可以运行git。



### usage

`python load.py`

### xmind

xmind样式如下，会根据图中的节点关系创建对应的目录层级关系。

![xmind](E:\github\LoadFromXmind\xmind.png)



### 运行效果

目录层级和xmind中的结构对应。

![运行效果](E:\github\LoadFromXmind\运行效果.png)