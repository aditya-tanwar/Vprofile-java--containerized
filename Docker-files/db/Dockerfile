FROM mysql:8.0.33
LABEL "Project"="vprofile"
LABEL "Author"="Akshay"

ENV MYSQL_ROOT_PASSWORD="admin123"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql