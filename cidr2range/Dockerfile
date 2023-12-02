# syntax=docker/dockerfile:1
FROM alpine:3.18.5

WORKDIR /cidr2range
COPY build/cidr2range ./
ENTRYPOINT ["/cidr2range/cidr2range"]
