# syntax=docker/dockerfile:1
FROM alpine:3.20.3

WORKDIR /cidr2range
COPY build/cidr2range ./
ENTRYPOINT ["/cidr2range/cidr2range"]
