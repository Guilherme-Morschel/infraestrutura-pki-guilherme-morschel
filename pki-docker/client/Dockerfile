FROM alpine:latest
RUN apk add --no-cache curl ca-certificates
COPY raiz.crt /usr/local/share/ca-certificates/raiz.crt
RUN update-ca-certificates
CMD ["sleep", "infinity"]
