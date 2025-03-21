# chatserver
集群聊天服务器和客户端源码 ；技术要点：c/c++、tcp、muduo、redis、mysql、nginx、cmake

1.编译方式：
cd build
rm -rf *
cmake ..
make
或者 自动编译脚本：./autobuild.sh

2.运行：
（1）需要nginx的负载均衡（配置好相关文件nginx.conf,并启动）
（2）运行服务器  /bin/ChatServer xxx.xxx.xxx.x port1
（2）运行客户端  /bin/ChatClient xxx.xxx.xxx.x port2
