ARG MYSQL_VERSION=${MYSQL_VERSION}
FROM mysql:${MYSQL_VERSION}


COPY my.cnf /etc/mysql/my.cnf

CMD ["mysqld"]

EXPOSE 3306
