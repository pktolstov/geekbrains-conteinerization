
FROM golang:1.17-buster

WORKDIR /app

COPY go.mod ./
COPY go.sum ./
RUN go mod download

COPY *.go ./

RUN go build -o /docker-go-app

EXPOSE 8080

CMD [ "/docker-go-app" ]
