FROM centos

ENV ANSIBLE_HOST_KEY_CHECKING False

RUN yum -y update && \
    yum -y install openssh-clients && \
    yum -y install epel-release && \
    yum -y install ansible

CMD /bin/bash

