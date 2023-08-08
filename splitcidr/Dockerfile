# syntax=docker/dockerfile:1
FROM alpine:3.18.3

WORKDIR /splitcidr
COPY build/splitcidr ./
ENTRYPOINT ["/splitcidr/splitcidr"]
