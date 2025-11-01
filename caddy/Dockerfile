FROM caddy:alpine

COPY caddy/ /etc/caddy/

EXPOSE ${PORT:-8443}

CMD ["caddy", "run", "--config", "/etc/caddy/Caddyfile", "--adapter", "caddyfile"]
