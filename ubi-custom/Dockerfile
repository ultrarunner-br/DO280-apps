FROM registry.access.redhat.com/ubi8/ubi:8.4-211

RUN yum install -y iputils
RUN yum install -y net-tools
RUN yum install -y iperf3
RUN yum clean all
RUN dnf install nmap

CMD ["/sbin/init"]
