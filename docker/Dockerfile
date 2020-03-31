FROM alpine
RUN apk update
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python py-pip && \
    pip install awscli
CMD tail -f /dev/null
