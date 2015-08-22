# official Debian Jessie
FROM debian:jessie
MAINTAINER Jose Rivero <work@josemrb.com>

# minimal utilities
RUN apt-get update && \
    apt-get install --no-install-recommends -y apt-utils git-core openssh-client wget sudo

# ansible dependencies
RUN apt-get install --no-install-recommends -y python-paramiko python-yaml python-jinja2 python-httplib2 python-setuptools python-pip

# install
RUN pip install ansible && \
    mkdir -p /etc/ansible && \
    echo '[local]\nlocalhost\n' > /etc/ansible/hosts

CMD ["/bin/bash"]
