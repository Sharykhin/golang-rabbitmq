FROM golang:1.12

WORKDIR /app

COPY go.mod .
COPY go.sum .

RUN go mod download

COPY . .

RUN go get github.com/githubnemo/CompileDaemon