# Use the official MySQL image as the base
FROM mysql:8.0

# Copy the initialization script to the container
COPY init.sql /docker-entrypoint-initdb.d/

# Set environment variables for MySQL
ENV MYSQL_ROOT_PASSWORD=rootpassword
ENV MYSQL_DATABASE=sampledb
ENV MYSQL_USER=appuser
ENV MYSQL_PASSWORD=apppassword

# Expose the default MySQL port
EXPOSE 3306
