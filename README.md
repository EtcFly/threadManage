
## threadMange
一个基于rt_thread的线程管理器，支持线程的重启和恢复


## 功能
   ###### 1 可自动检测卡死的僵尸线程，并实现释放(包括对原线程申请的动态堆内存的释放)
   ###### 2 通过finsh命令实现对各管理线程资源情况进行查看  
  
	
## 操作
   ###### 1 保证开启一个优先级最高的线程用于线程管理器线程
   ###### 2 其他线程需要在启动时调用注册接口
   
   
   123
	
