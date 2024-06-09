# Etapa de construcción
FROM golang:1.18 AS builder
WORKDIR /app
COPY . .
RUN go mod download
RUN CGO_ENABLED=0 GOOS=linux GOARCH=amd64 go build -o /app/main .

# Etapa de ejecución
FROM alpine:latest
WORKDIR /root/
COPY --from=builder /app/main .
COPY configs configs/
CMD ["./main"]