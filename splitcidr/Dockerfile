# syntax=docker/dockerfile:1
FROM alpine:3.22.0

WORKDIR /splitcidr
COPY build/splitcidr ./
ENTRYPOINT ["/splitcidr/splitcidr"]
