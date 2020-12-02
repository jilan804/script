#!/bin/bash 
#change to the /tmp
cd /tmp
#Download the java
wget -c --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u131-b11/d54c1d3a095b4ff2b6607d096fa80163/jdk-8u131-linux-x64.rpm
#install the rpm
rpm -ivh jdk-8u131-linux-x64.rpm
#change to the opt
cd /opt
#Download the Tomcat
wget http://apachemirror.wuchna.com/tomcat/tomcat-9/v9.0.38/bin/apache-tomcat-9.0.38-windows-x64.zip
#unzip the tomcat
unzip apache-tomcat-9.0.38-windows-x64.zip
#delete the zip file
rm -f apache-tomcat-9.0.38-windows-x64.zip
#rename
mv apache-tomcat-9.0.38 tomcat9
#change the permissions for the scripts in the bin directory 
cd tomcat9/bin
chmod 755 *.sh 
#start the tomcat 
./startup.sh 

