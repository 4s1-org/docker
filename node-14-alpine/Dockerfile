FROM node:14.19.1-alpine

LABEL maintainer="Steffen <steffen@4s1.de>"
LABEL org.opencontainers.image.description Node 14 Alpine Image for 4s1-org

ENV TZ=Europe/Berlin
ENV LANG=de_DE.UTF-8

RUN npm i pnpm -g && \
    pnpm config set store-dir .pnpm-store
