FROM centos:latest

COPY bin/main.sh /usr/local/

RUN yum -q -y install python3

CMD ["python3", "/usr/local/main.sh"]
