# Kubernetes-Tutorial

# mm_wiki

安装
1. 自助安装
打开 https://github.com/phachon/mm-wiki/releases 找到对应平台的版本下载编译好的压缩包

Linux 平台


# 创建目录
```
$ mkdir mm_wiki
$ cd mm_wiki
# 以 linux amd64 为例，下载最新版本压缩包
# https://github.com/phachon/mm-wiki/releases 自行下载 wget http://
# 解压到当前目录
$ tar -zxvf mm-wiki-linux-amd64.tar.gz
# 进入程序安装目录
$ cd install
# 执行安装程序，默认端口为 8090，指定其他端口加参数 --port=8087
$ ./install
# 浏览器访问 http://ip:8090 进入安装界面，完成安装配置
# Ctrl + C 停止 install 程序, 启动 MM-Wiki 系统
$ cd ..
$ ./mm-wiki --conf conf/mm-wiki.conf
# 浏览器访问你监听的 ip 和端口
# 开始 MM-Wiki 的使用之旅吧！
```
