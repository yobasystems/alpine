FROM scratch

ARG BUILD_DATE
ARG VCS_REF

LABEL maintainer="Dominic Taylor <dominic@yoba.systems>" \
    architecture="amd64/x86_64" \
    alpine-version="3.21.3" \
    build="16-Jun-2025" \
    org.opencontainers.image.title="alpine" \
    org.opencontainers.image.description="Container image running Alpine Linux" \
    org.opencontainers.image.authors="Dominic Taylor <dominic@yoba.systems>" \
    org.opencontainers.image.vendor="Yoba Systems" \
    org.opencontainers.image.version="3.21.3" \
    org.opencontainers.image.url="https://hub.docker.com/r/yobasystems/alpine/" \
    org.opencontainers.image.source="https://github.com/yobasystems/alpine" \
    org.opencontainers.image.revision=$VCS_REF \
    org.opencontainers.image.created=$BUILD_DATE

ADD alpine-minirootfs-3.21.3-x86_64.tar.gz /
CMD ["/bin/sh"]
