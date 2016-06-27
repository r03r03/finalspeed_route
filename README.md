# finalspeed_route
用于路由器上的finalspeed，手动配置，将配置文件和finalspeed同目录


插楼简单说一下步骤：

1.参考以下网址安装debian8
https://www.hqt.ro/how-to-install-debian-jessie-arm/

2.进入debian，执行以下命令：
apt-get update
apt-get upgrade
apt-get install openjdk-7-jre-headless libpcap0.8 libjna-java

3.下载本帖提供的无UI版fs，解压到deian里的任意位置

4.添加两个配置文件client_config.json和port_map.json

5.执行java -jar finalspeed.jar -b
