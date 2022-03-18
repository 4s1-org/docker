FROM node:14.19.1-buster
LABEL maintainer="Steffen <steffen@4s1.de>"

ENV TZ=Europe/Berlin
ENV LANG=de_DE.UTF-8

RUN npm i pnpm -g && \
    pnpm config set store-dir .pnpm-store
