FROM golang:1.14.9-alpine
RUN mkdir /app
COPY main.go /app
WORKDIR /app
RUN go build -o webserver
ENTRYPOINT ["/app/webserver"]