# openwrt-modify

用于修改OPENWRT已编译完成固件的脚本

解压：

	./modify.sh e xxx.bin
列出目录

	./rm.sh

删除某个软件：

	./rm.sh xxxx

打包：

	./modify.sh create newfirmware.bin
	
清空环境：

	./modify.sh clean

其中：
	mksquashfs4
	modify.sh
	padjffs2
	unsquashfs4
来自：http://www.xiangtaole.com/jingyan/3065
