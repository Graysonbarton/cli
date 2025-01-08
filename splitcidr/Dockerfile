# syntax=docker/dockerfile:1
FROM alpine:3.21.1

WORKDIR /splitcidr
COPY build/splitcidr ./
ENTRYPOINT ["/splitcidr/splitcidr"]
