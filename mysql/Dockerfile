FROM mysql:8.0
COPY ./hms.sql /docker-entrypoint-initdb.d/
RUN chmod 644 /docker-entrypoint-initdb.d/hms.sql