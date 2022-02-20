ARG BUILD_FROM
FROM $BUILD_FROM

RUN apk add --no-cache \
        rsync

ENV MULTIDICT_NO_EXTENSIONS=1

# Copy data
COPY rootfs /
