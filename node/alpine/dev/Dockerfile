FROM registry.gitlab.com/4s1/docker/node:14-alpine

ENV GIT_AUTHOR_NAME=Bot
ENV GIT_AUTHOR_EMAIL=bot@4s1.de
ENV GIT_COMMITTER_NAME=Bot
ENV GIT_COMMITTER_EMAIL=bot@4s1.de

RUN apk update && apk upgrade && \
    apk add --no-cache git openssh curl
