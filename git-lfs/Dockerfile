FROM ghcr.io/cocogitto/cog:7.0.0

RUN apk update && \
    apk upgrade && \
    apk --no-cache add git-lfs=3.7.1-r0 && \
    rm -rf /var/cache/apk/*
