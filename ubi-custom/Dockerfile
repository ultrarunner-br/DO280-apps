FROM registry.access.redhat.com/ubi8/ubi:8.4-211

RUN yum install -y \
  iputils \
  net-tools \
  && yum clean all
RUN dnf install nmap

CMD ["/sbin/init"]
