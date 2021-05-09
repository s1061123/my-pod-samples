FROM docker.io/centos/tools:latest

ADD nginx.repo /etc/yum.repos.d
RUN yum install -y nginx && \
    systemctl enable nginx

CMD /sbin/init
