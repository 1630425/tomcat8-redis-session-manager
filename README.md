# tomcat8-redis-session-manager
tomcat8-redis-session-manager基于tomcat-redis-session-manager

tomcat8下载以下3个jar放入tomcat/lib目录下即可
在tomcat-redis-session-manager\build\libs目录下，可以找到编译成功的jar文件：
tomcat-redis-session-manager-2.0.0.jar

在tomcat-redis-session-manager\build\libs-jar目录下，可以找到另外2个依赖的jar文件：（或者从maven里下载）
commons-pool2-2.4.2.jar
jedis-2.9.0.jar


手动编译
gradle build
gradle build -x test copyJars