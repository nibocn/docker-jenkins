FROM jenkins:2.46.1

MAINTAINER Richard <nibocn@gmail.com>

ENV TZ=Asia/Shanghai

RUN mkdir -p ${JENKINS_HOME}/.ssh

COPY config ${JENKINS_HOME}/.ssh/
