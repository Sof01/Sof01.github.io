# Sof01.github.io
github domain name for whatever purpose I may find for it in the future.


curl -O https://dlcdn.apache.org/tomcat/tomcat-10/v10.1.24/bin/apache-tomcat-10.1.24.tar.gz ;
tar zxvf apache-tomcat-10.1.24.tar.gz ;
mv apache-tomcat-10.1.24 /usr/libexec/tomcat10 ;
useradd -M -d /usr/libexec/tomcat10 tomcat ;
chown -R tomcat:tomcat /usr/libexec/tomcat10 ;
