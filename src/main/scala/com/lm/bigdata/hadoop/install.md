# data_document
# hadoop安装
注意：apache官网提供的hadoop-2.x的安装包是在32位操作系统编译的，因为hadoop依赖一些C++的本地库，\
所以如果在64位的操作上安装hadoop-2.4.1就需要重新在64操作系统上重新编译\
安装 yum install psmisc\
Killall -9 java\
安装 glibc-headers 和  g++  命令如下: \
 $yum install glibc-headers\
 $ yum install gcc-c++\
安装make和cmake\
$yum install make \
$yum install cmake 

前提准备：\
1.修改Linux主机名\
vim /etc/sysconfig/network \
NETWORKING=yes \
HOSTNAME=hadoop01    ### \

