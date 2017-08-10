常常，我们搭建shadowsockets的服务器是CentOS 6.0 或者 7.0，当然其它版本的 Linux 各位可以尝试。

作者搭建时用的命令：

第一行：

wget --no-check-certificate https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks.sh

第二行，给脚本加权限：chmod +x shadowsocks.sh

第三行，运行脚本：./shadowsocks.sh 2>&1 | tee shadowsocks.log


那么，这里的 "搭建脚本.sh" 是什么意思呢？？其实就是做个备份，如果哪儿天上面这个地址的服务器宕了，我们可以用自己的脚本搭建。

操作步骤有三步：

1.把脚本弄到服务器中。
2.给脚本加权限，否则执行不了。
3.运行脚本。


搭建完成后的配置方法：http://www.uudaili.org/windows-shadowsocks.html