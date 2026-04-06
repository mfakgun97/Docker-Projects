# pull the official MySQL image from the Docker Hub
FROM mysql:8.0

# set the enviroment variables for MySQL
ENV MYSQL_ROOT_PASSWORD=demopassword
ENV MYSQL_DATABASE=demodb

# copy the initialization script to the Docker Image
COPY init.sql /docker-entrypoint-initdb.d/

# expose the default MySQL port
EXPOSE 3307
