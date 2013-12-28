How to initialize toyhouse.ie.tsinghua.edu.cn
==========

## Initializing xlp.uucampus.com

1.进入/home/edusns/efilesys，执行sh deploy.sh，启动分布式文件系统的web端
root@toyhouse-PowerEdge-2950:/home/edusns/efilesys# sh deploy.sh
 
2.efilesys-start-server来启动分布式文件系统的thrift服务：
root@toyhouse-PowerEdge-2950:/home/edusns/efilesys# nohup efilesys-start-server &
 
3.启动tomcat
 
root@toyhouse-PowerEdge-2950:/home/software/apache-tomcat-7.0.29/bin# sh startup.sh
 
4.启动chat
 
root@toyhouse-PowerEdge-2950:/home/edusns/chat# sh start.sh 