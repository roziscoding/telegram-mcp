FROM caddy:alpine

COPY caddy/ /etc/caddy/

EXPOSE ${PORT:-8443}

ENV CADDY_ADMIN=${CADDY_ADMIN}

CMD ["caddy", "run", "--config", "/etc/caddy/Caddyfile", "--adapter", "caddyfile"]
