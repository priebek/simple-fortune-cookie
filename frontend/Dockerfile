FROM golang:1.17
EXPOSE 8080

WORKDIR /go/src/app
COPY . .

RUN go build
CMD ["go", "run", "frontend"]