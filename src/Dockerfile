FROM alpine:latest
ARG DIFFY_VERSION=0.1.23
RUN apk update && \
    apk add bash git openssh openssl php php-openssl php-phar php-iconv && \
    wget -O /usr/local/bin/diffy https://github.com/DiffyWebsite/diffy-cli/releases/download/${DIFFY_VERSION}/diffy.phar && \
    chmod u+x /usr/local/bin/diffy