libjpeg9.0编译
mac：
1. 首先获取源码：https://www.ijg.org/files/
2. 安装autoconf(本次编译成功，autoconf版本为2.71) 安装指令：brew install autoconf
3. 安装automake(本次编译成功，automake版本号为1.16.5) 安装指令：brew install automake
4. 安装libtool(本次编译成功，安装libtool版本号为2.4.7)安装指令：brew install libtool
5. 执行指令 autoreconf -fiv
6. ./configure
7. 执行make，完成编译
