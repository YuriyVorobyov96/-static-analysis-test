# FROM mysql:8.0.19
FROM mysql:5.7

# Copy the database schema to the /data directory
ADD ./db.sql /docker-entrypoint-initdb.d
