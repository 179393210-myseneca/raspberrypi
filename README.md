# raspberrypi
IoT: TML and Kafka on Raspberry PI
IF having issues with java you may need to re-install

sudo apt install --reinstall default-jre default-jdk default-jre-headless default-jdk-headless openjdk-11-jdk openjdk-11-jdk-headless openjdk-11-jre openjdk-11-jre-headless openjdk-8-jdk openjdk-8-jdk-headless openjdk-8-jre openjdk-8-jre-headless

Note you may need to run: 
1. sudo rm /var/lib/dpkg/info/* 
2. sudo dpkg --configure -a

If you have MySQL issues try this:
ps -A|grep mysql
sudo pkill mysql
ps -A|grep mysqld
sudo pkill mysqld
service mysql restart
