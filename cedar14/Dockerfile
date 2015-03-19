FROM ubuntu-debootstrap:14.04
COPY ./cedar-14.sh /tmp/build.sh
ENV LC_ALL pl_PL.UTF-8
RUN LC_ALL=pl_PL.UTF-8 DEBIAN_FRONTEND=noninteractive /tmp/build.sh
