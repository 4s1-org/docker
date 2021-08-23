ARG NODE_VERSION=unknown

FROM registry.gitlab.com/yellowgarbagegroup/docker-images/node:${NODE_VERSION}

RUN apk update && apk upgrade && \
    apk add --no-cache git openssh curl
