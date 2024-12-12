# syntax=docker/dockerfile:1
FROM alpine:3.21.0

WORKDIR /cidr2range
COPY build/cidr2range ./
ENTRYPOINT ["/cidr2range/cidr2range"]
