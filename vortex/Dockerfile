FROM golang:1.10.3-alpine3.7

RUN mkdir -p /app
WORKDIR /app
ENV SRC_DIR=/go/src/github.com/alexsjones/vortex
RUN go get -v github.com/alexsjones/vortex
