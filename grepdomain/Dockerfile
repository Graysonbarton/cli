# syntax=docker/dockerfile:1
FROM alpine:3.23.3

WORKDIR /grepdomain
COPY build/grepdomain ./
ENTRYPOINT ["/grepdomain/grepdomain"]
