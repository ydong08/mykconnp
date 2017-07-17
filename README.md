# mykconnp
Kernel Connection Pool


Kconnp是Kernel Connection Pool的简写，是基于Linux内核的线程安全连接池，
减少由频繁建立和释放连接带来的系统开销，提升服务响应速度，支持跨语言、多服务连接池。
特性：
    1、支持跨语言（PHP，JAVA，python，C，C++，Perl， ... ）共享连接池
    2、支持多服务（Memcache，Redis，MySQL，Oracle，... ）建立连接池
    3、线程安全