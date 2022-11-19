# syntax=docker/dockerfile:1

FROM golang:latest

WORKDIR /app

COPY . .

RUN go mod download


RUN go build -o /pictureminer

EXPOSE 9000

CMD [ "/pictureminer" ]r scan