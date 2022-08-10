# lsquic-demo
Example lsquic client/server

编译命令：
cmake . & make

测试指令：
./server 127.0.0.1 12345

./client 127.0.0.1 12346 127.0.0.1 12345


参考依赖库拷贝获取：
1.git clone https://github.com/dtikhonov/lsquic-tutorial.git
2.cd lsquic-tutorial
3.拉取更新依赖：
git submodule update --init --recursive
