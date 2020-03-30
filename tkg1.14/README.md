TKG=1.14  
CNI=Calico 3.75  
VIO=6.0.0.1  

一共4个文件夹  
•	main  - heat stack运行的脚本  
•	lib  - 各种后台脚本  
•	repos-img  - 运行过程中需要的各种image文件  
•	repos-yaml  - 运行过程中需要的各种yaml文件  

部署步骤：
1.	创建http server（推荐使用CentOS VM，为了方便说明，假定IP地址为192.168.0.10），将repos-img和repos-yaml文件上传到http server。
http server配置方式如下：

2.	创建OpenStack client（推荐使用CentOS VM，假定IP地址为192.168.0.20），确认OpenStack Client可以和VIO正常通信。
OpenStack Client配置方式如下：
