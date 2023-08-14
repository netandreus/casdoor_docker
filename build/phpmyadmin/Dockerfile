FROM phpmyadmin:5.2.1

COPY docker-phpmyadmin-healthcheck /usr/local/bin
RUN apt-get update \
    &&  apt-get -y install wget telnet net-tools mc \
    && chmod +x /usr/local/bin/docker-phpmyadmin-healthcheck