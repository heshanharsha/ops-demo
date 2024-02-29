docker build -t nginx-otel --platform linux/amd64 .
docker run --platform linux/amd64 --rm -p 8080:80 nginx-otel
