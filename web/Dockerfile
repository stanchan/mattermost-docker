FROM stanchan/caddy:1.0.3

RUN apk add --no-cache curl

COPY ./Caddyfile /etc/Caddyfile

#Healthcheck to make sure container is ready
HEALTHCHECK CMD curl --fail http://127.0.0.1:80 || exit 1
