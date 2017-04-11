FROM jenkins:latest

MAINTAINER Richard <nibocn@gmail.com>

ENV TZ=Asia/Shanghai

RUN mkdir -p ${JENKINS_HOME}/.ssh

COPY config ${JENKINS_HOME}/.ssh/
