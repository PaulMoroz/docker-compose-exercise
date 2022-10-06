# This Docker container is based on https://hub.docker.com/_/mysql/
FROM mariadb:10.8

# Add the movies.sql file to the container
# The mysql image has a script which will load all sql files from this directory
COPY database.sql /docker-entrypoint-initdb.d/
