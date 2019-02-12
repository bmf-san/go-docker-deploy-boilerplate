# Builder Container
FROM golang:1.11.0-alpine3.8 as builder
WORKDIR /usr/local/bin
COPY ./src .
RUN apk add --no-cache git
RUN go get github.com/pilu/fresh
CMD ["fresh"]
