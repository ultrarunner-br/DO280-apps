FROM registry.access.redhat.com/ubi8:8.0

RUN yum install -y \
  iputils \
  tcpdump \
  net-tools \
  iperf3 \
  && yum clean all

RUN dnf install nmap

CMD ["/sbin/init"]
