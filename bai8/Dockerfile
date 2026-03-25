# Base image PostgreSQL 15
FROM postgres:15

# Thiết lập biến môi trường cho user/database mặc định
ENV POSTGRES_USER=admin
ENV POSTGRES_PASSWORD=admin123
ENV POSTGRES_DB=mydb

# Copy file SQL vào thư mục init
COPY init.sql /docker-entrypoint-initdb.d/

# Expose port PostgreSQL
EXPOSE 5432