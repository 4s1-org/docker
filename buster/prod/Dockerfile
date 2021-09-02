ARG NODE_VERSION=unknown

FROM node:${NODE_VERSION}
LABEL maintainer="Steffen <yellowgarbagebag@4s1.de>"

ENV GIT_AUTHOR_NAME=YellowGarbageBot
ENV GIT_AUTHOR_EMAIL=yellowgarbagebot@4s1.de
ENV GIT_COMMITTER_NAME=YellowGarbageBot
ENV GIT_COMMITTER_EMAIL=yellowgarbagebot@4s1.de

ENV TZ=Europe/Berlin
ENV LANG=de_DE.UTF-8

RUN npm i pnpm -g
