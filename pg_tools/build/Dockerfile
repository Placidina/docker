# vim:set ft=dockerfile:
FROM centos:7

LABEL maintainer="Alan Placidina Maria <alanplacidina@gmail.com>"

RUN yum update -y \
    && yum install -y libconfig-devel postgresql-devel make gcc-c++

WORKDIR /src/github.com/placidina/pg_tools