FROM kana1/alpine-openjdk-jdk8

# Environment for Bamboo
ENV BAMBOO_VERSION=6.2.2 \
BAMBOO_HOME=/home/bamboo

# Expose ports (web/agent)
EXPOSE 8085 54663

RUN apk add --no-cache --update \
    ca-certificates curl tar

# Bamboo installation script ?
