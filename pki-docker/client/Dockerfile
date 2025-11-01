FROM curlimages/curl:latest

WORKDIR /work

# Copiar apenas o certificado da AC Raiz (único confiado)
COPY raiz.crt /usr/local/share/ca-certificates/raiz.crt

# Atualizar a store de certificados do sistema
RUN update-ca-certificates || true

CMD ["sleep", "infinity"]
