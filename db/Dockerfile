FROM amd64/mariadb:10.3.22

#Healthcheck to make sure container is ready
HEALTHCHECK CMD mysqladmin -h 127.0.0.1 -u root -p$MYSQL_ROOT_PASSWORD status || exit 1
