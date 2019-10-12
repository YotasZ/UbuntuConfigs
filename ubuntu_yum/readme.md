配置yum
1.安装yum

apt-get install yum

2.配置yum源

由于是Ubuntu没有yum源，所以要想使用yum安装软件必须要配置yum安装源。将本文件夹下的两个文件复制到/etc/yum/repos.d/目录下.

3.执行配置

在终端输入

yum makecache

即可完成在Ubuntu中安装yum


# 注意： plug修改的文件中，将/etc/yum/repos.d/下的两个文件的参数gpgcheck=1改为了0，意味着在下载的过程中不需要检查软件的秘钥。（目前没有找到ubuntu下对应的秘钥）
