FROM alpine:latest
MAINTAINER WeiguoLiu <liuwg-a@glodon.com>
USER root

RUN apk update
RUN apk add nodejs
RUN apk add npm
RUN npm --registry https://registry.npm.taobao.org install pm2 -g