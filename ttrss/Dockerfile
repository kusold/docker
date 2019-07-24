FROM skyr0/ttrss

RUN set -xe && \
    apk update && \
    apk add --no-cache --virtual=run-deps \
      php7-ldap && \
    rm -rf /var/cache/apk/*

