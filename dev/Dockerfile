ARG NODE_VERSION=unknown

FROM registry.gitlab.com/yellowgarbagegroup/docker-images/node:${NODE_VERSION}

ENV GIT_AUTHOR_NAME=YellowGarbageBot
ENV GIT_AUTHOR_EMAIL=yellowgarbagebot@4s1.de
ENV GIT_COMMITTER_NAME=YellowGarbageBot
ENV GIT_COMMITTER_EMAIL=yellowgarbagebot@4s1.de

RUN apk update && apk upgrade && \
    apk add --no-cache git openssh curl
