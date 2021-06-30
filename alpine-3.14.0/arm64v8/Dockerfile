FROM scratch

ARG BUILD_DATE
ARG VCS_REF

LABEL maintainer="Dominic Taylor <dominic@yobasystems.co.uk>" \
    architecture="arm64v8/aarch64" \
    alpine-version="3.14.0" \
    build="30-Jun-2021" \
    org.opencontainers.image.title="alpine" \
    org.opencontainers.image.description="Docker image running on Alpine Linux" \
    org.opencontainers.image.authors="Dominic Taylor <dominic@yobasystems.co.uk>" \
    org.opencontainers.image.vendor="Yoba Systems" \
    org.opencontainers.image.version="v3.14.0" \
    org.opencontainers.image.url="https://hub.docker.com/r/yobasystems/alpine/" \
    org.opencontainers.image.source="https://github.com/yobasystems/alpine" \
    org.opencontainers.image.revision=$VCS_REF \
    org.opencontainers.image.created=$BUILD_DATE

ADD alpine-minirootfs-3.14.0-aarch64.tar.gz /
CMD ["/bin/sh"]
