FROM golang:alpine as builder 

WORKDIR /go/src/app

ENV GO11MODULE=on

RUN go get github.com/cespare/reflex

COPY go.mod .

COPY go.sum . 

RUN go and download

