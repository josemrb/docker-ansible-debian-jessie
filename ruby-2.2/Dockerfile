FROM ansible-debian-jessie:base
MAINTAINER Jose Rivero <work@josemrb.com>

RUN mkdir -p /tmp/ansible/ruby
ADD ansible /tmp/ansible/ruby
WORKDIR /tmp/ansible/ruby

RUN ansible-playbook default.yml -c local

ENV PATH /root/.rbenv/bin:$PATH

CMD ["/bin/bash"]
