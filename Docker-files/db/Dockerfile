FROM mysql:8.0.33-oracle
LABEL "project"="vprofile"
LABEL "Author"="tejicld"

ENV MYSQL_PASSWORD="vprodpass"
ENV MYSQL_USER="accounts"
COPY db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql
