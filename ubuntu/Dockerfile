FROM ubuntu:latest

COPY bin/main.sh /usr/local/

RUN apt-get update \
    && apt-get install -y python3

CMD ["python3", "/usr/local/main.sh"]
