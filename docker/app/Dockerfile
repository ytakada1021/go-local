FROM golang:1.21

RUN go install github.com/cosmtrek/air@v1.45.0

COPY .air.toml /

CMD ["air", "-c", "/.air.toml"]
