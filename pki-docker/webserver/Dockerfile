FROM nginx:stable-alpine

# Copiar o certificado e chave
COPY web.crt /etc/ssl/certs/web.crt
COPY web.key /etc/ssl/private/web.key

# Copiar configuração HTTPS
COPY default.conf /etc/nginx/conf.d/default.conf

EXPOSE 443
