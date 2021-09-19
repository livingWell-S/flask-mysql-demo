FROM --platform=linux/x86_64 mysql:5.7
EXPOSE 3306

ADD ./my.cnf /etc/mysql/conf.d/my.cnf

CMD ["mysqld"]