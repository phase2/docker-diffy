FROM alpine:latest
RUN apk update && \
    apk add openssl php php-openssl php-phar php-iconv && \
    wget -O /usr/local/bin/diffy https://github.com/DiffyWebsite/diffy-cli/releases/download/0.1.22/diffy.phar && \
    chmod u+x /usr/local/bin/diffy