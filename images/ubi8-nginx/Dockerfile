FROM registry.access.redhat.com/ubi8/ubi:latest

RUN dnf install -y iptables nginx iproute iputils && \
    systemctl enable nginx

CMD /sbin/init
