about haproxy:
 下载
    wget http://www.haproxy.org/download/1.9/src/haproxy-1.9.0.tar.gz
    解压
    tar -zxvf haproxy-1.9.0.tar.gz
    mv haproxy-1.9.0.tar.gz haproxy
    cd haproxy
    安装

[root@localhost haproxy]# uname -a
Linux localhost 3.10.0-514.2.2.el7.x86_64 #1 SMP Tue Dec 6 23:06:41 UTC 2016 x86_64 x86_64 x86_64 GNU/Linux 
#TARGET：系统内核版本， ARCH：系统架构，PREFIX：安装目录
make TARGET=linux3100 ARCH=x86_64 PREFIX=/usr/local/haproxy
make install PREFIX=/usr/local/haproxy

    配置：
    vim /usr/local/haproxy/haproxy.cfg
    
