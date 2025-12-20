FROM jenkins/jenkins:lts-jdk17

USER root

ENV TZ=Asia/Shanghai

RUN ln -sf /usr/share/zoneinfo/$TZ /etc/localtime && \
    echo $TZ >/etc/timezone
