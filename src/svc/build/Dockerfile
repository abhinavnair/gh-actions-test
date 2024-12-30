FROM alpine:3.21.0

LABEL org.opencontainers.image.source=https://github.com/abhinavnair/gh-actions-test
LABEL org.opencontainers.image.description="Just testing some actions"

RUN apk --no-cache add tzdata ca-certificates

COPY ./build/binaries/ /

USER 10001
