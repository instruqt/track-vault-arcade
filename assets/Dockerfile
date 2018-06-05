FROM vault:0.10.1

RUN apk add --update bash jq curl

COPY server.hcl /etc/vault/server.hcl

CMD ["server", "-config", "/etc/vault/server.hcl"]