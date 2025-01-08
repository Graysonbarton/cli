# syntax=docker/dockerfile:1
FROM alpine:3.21.1

WORKDIR /cidr2range
COPY build/cidr2range ./
ENTRYPOINT ["/cidr2range/cidr2range"]
