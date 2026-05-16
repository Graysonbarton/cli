# syntax=docker/dockerfile:1
FROM alpine:3.21.0

WORKDIR /splitcidr
COPY build/splitcidr ./
ENTRYPOINT ["/splitcidr/splitcidr"]
