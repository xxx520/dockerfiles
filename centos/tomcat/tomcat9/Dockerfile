from centos:7.5.1804
MAINTAINER x
RUN yum -y install openssh-clinets net-tools expect java-1.8.0-openjdk && \
	mkdir /opt/tomcat9
ADD tomcat9 /opt/tomcat9

CMD ["/usr/bin/init"]