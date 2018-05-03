FROM mysql:5.7

LABEL maintainer="eliu <eliuhy@163.com>"

ENV TZ Asia/Shanghai

COPY hap.cnf /etc/mysql/conf.d/

RUN set -x \
    && echo "Asia/Shanghai" > /etc/timezone \
    && dpkg-reconfigure -f noninteractive tzdata
