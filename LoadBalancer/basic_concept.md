## Load Balancer相关的一些基本概念

LB 表示 Load Balancer  
TG 表示 Target Group  
L  表示 Listener  

LB本质是一个计算机，这个机器负责接收流量，分发流量  
Listener本质是在LB里面一段程序的运行实例（进程），这个进程负责监听网络入口流量，筛选允许通过的流量，比如80端口的HTTP协议的流量  
TG是目的地流量的接收端口  

配置一个LB，不光要创建LB，还要配置它的L和TG
