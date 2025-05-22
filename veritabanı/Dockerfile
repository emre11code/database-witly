FROM alpine:latest

RUN apk --no-cache add ca-certificates

WORKDIR /app

COPY . .

RUN chmod +x pocketbase start.sh

EXPOSE 8080

CMD ["./start.sh"]
