FROM alpine:latest
Workdir /app
copy main.go /app
RUN go build main.go
cmd ["/main"]