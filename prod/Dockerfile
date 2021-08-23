ARG NODE_VERSION=unknown

FROM node:${NODE_VERSION}

ENV TZ=Europe/Berlin
ENV LANG=de_DE.UTF-8

RUN npm i pnpm -g && \
    mkdir -p /app
