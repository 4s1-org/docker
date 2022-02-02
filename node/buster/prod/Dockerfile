FROM node:17.4.0-buster
LABEL maintainer="Steffen <steffen@4s1.de>"

ENV TZ=Europe/Berlin
ENV LANG=de_DE.UTF-8

RUN npm i pnpm -g && \
    pnpm config set store-dir .pnpm-store
