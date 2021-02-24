FROM postgres:11-alpine

ENV TZ="Asia/Jakarta"
RUN apk update && \
    apk add tzdata && \
    cp /usr/share/zoneinfo/${TZ} /etc/localtime

