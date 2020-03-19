FROM stanchan/caddy:1.0.3

COPY ./Caddyfile /etc/Caddyfile

#Healthcheck to make sure container is ready
HEALTHCHECK CMD curl --fail http://localhost:80 || exit 1
