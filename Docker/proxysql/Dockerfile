FROM proxysql/proxysql:2.4.8
RUN apt-get update -y --fix-missing
RUN apt-get install -y default-mysql-client
ADD proxysql.cnf /etc/