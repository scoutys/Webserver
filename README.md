# Webserver
一个轻量化的web服务器项目。

http.h是http连接的头文件，用于http.cpp中引用
locker.h是封装了信号量、互斥量、条件变量的头文件
thread_pool.h文件是线程池，创建threadnum个线程，并调用pthread_detach()分离线程，线程结束，自动回收资源。
log.h封装日志头文件，用于log.cpp中引用
lst_timer.h封装定时器，用于lst_timer.cpp中
main.cpp是主程序，调用各个组件
