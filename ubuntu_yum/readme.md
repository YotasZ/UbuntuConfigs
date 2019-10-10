配置yum
1.安装yum

apt-get install yum

2.配置yum源

由于是Ubuntu没有yum源，所以要想使用yum安装软件必须要配置yum安装源。将本文件夹下的两个文件复制到/etc/yum/repos.d/目录下.

3.执行配置

在终端输入

yum makecache

即可完成在Ubuntu中安装yum
