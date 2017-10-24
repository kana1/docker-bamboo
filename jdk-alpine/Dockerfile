FROM alpine:3.6

LABEL container=openjre \
      container.version=1.0 \
      openjre.version=8

# Default to UTF-8 file.encoding
ENV LANG C.UTF-8

RUN apk add --update --no-cache \
  tini && \ # installing a init process 
  openjdk8 && \
  bash

ENV JAVA_HOME /usr/lib/jvm/java-1.8-openjdk
