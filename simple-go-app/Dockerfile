FROM golang

WORKDIR /work
COPY go.mod main.go /work

RUN go build -o hello .

CMD ["/work/hello"]
