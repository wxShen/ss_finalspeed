# ss_finalspeed
对于windows 可直接使用客户端下载的内容
系统需安装 java 运行环境 ,Linux 还需安装 libpcap.
Ubuntu,Debian 安装 libpcap: apt-get -y install libpcap-dev
Centos 安装 libpcap: yum -y install libpcap

安装 : 下载解压 .
运行 : 打开终端 , 假设 finalspeed_client.jar 所在路径为 /fsclient , 先切换到该路径 cd /fsclient ,
	然后执行 sudo java -jar finalspeed_client.jar , 前面加 sudo, 因为必须以 root 权限运行 , 如果没有 root 权限 , 会无法启用 tcp 协议 .


