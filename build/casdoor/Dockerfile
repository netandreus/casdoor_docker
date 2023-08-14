FROM casbin/casdoor:v1.388.0

COPY docker-casdoor-healthcheck /usr/local/bin
RUN sudo chmod +x /usr/local/bin/docker-casdoor-healthcheck
RUN sudo apk update && \
    sudo apk add busybox-extras bash mc
