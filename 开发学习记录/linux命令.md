
firewall-cmd --reload 重新防火墙端口

firewall-cmd --permanent --add-port=5014/tcp 添加指定端口

firewall-cmd --permanent --remove-port=50010/tcp 删除指定端口

ps -ef | grep userauth 查找指定服务

**lsof -i :端口号**


找不到/usr/share/fonts 这个文件夹 使用以下命令

1.yum -y install fontconfig

2.yum -y install ttmkfdir

3.ttmkfdir -e /usr/share/X11/fonts/encodings/encodings.dir

安装字体步骤 需要把字体复制到fonts下 需要TTF格式

cd /usr/share/fonts/

mkfontscale

mkfontdir

fc-cache

使用fc-list :lang=zh 查看是否已经安装完毕