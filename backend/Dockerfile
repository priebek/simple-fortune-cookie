FROM golang:1.17
EXPOSE 9000

WORKDIR /go/src/app
COPY . .

RUN go build
CMD ["go", "run", "backend"]