0、适用于用apt-get安装的软件

1、查看已安装软件  apt list --installed |grep protobuf

2、查看某个包所在位置 dpkg -L libprotobuf-dev

3、删除某个包 apt-get purge libprotobuf-dev
