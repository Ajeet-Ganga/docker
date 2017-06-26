# Template file for Java development
# Confirmed working of:
# - OpenJDK 9
# - Python3 
#	+ pip
# - maven
# - git
# - ping
# - vim
# - curl

# Base repo: https://hub.docker.com/_/openjdk/
# Base docker file: https://github.com/docker-library/openjdk/blob/master/9-jdk/Dockerfile

FROM openjdk:9

# To install python3.6
# Don't be peasant use p3.
RUN apt-get update && apt-get install -q -y \
	python3.6 \
	maven \
	vim

RUN curl https://bootstrap.pypa.io/get-pip.py | python3.6

## Details
# mvn --version
# Apache Maven 3.5.0
# Maven home: /usr/share/maven
# Java version: 9-Debian, vendor: Oracle Corporation
# Java home: /usr/lib/jvm/java-9-openjdk-amd64
# Default locale: en, platform encoding: UTF-8
# OS name: "linux", version: "4.9.8-moby", arch: "amd64", family: "unix"
# Python 3.6.2rc1
# VIM - Vi IMproved 8.0 (2016 Sep 12, compiled Apr 23 2017 12:10:29)

# git --version
# git version 2.11.0