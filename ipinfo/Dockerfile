# syntax=docker/dockerfile:1
FROM alpine:3.22.0

WORKDIR /ipinfo
COPY build/ipinfo ./
ENTRYPOINT ["/ipinfo/ipinfo"]
