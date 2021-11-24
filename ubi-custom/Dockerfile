FROM registry.access.redhat.com/ubi8/ubi:8.4-211

RUN dnf install -y \
  iputils \
  net-tools \
  bind-utils \
  ethtool \
  nmap \
  procps-ng \
  && dnf clean all

CMD ["/sbin/init"]
