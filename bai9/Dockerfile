# Base image Redis mới nhất
FROM redis:latest

# Copy file cấu hình vào container
COPY redis.conf /usr/local/etc/redis/redis.conf

# Expose port
EXPOSE 6379

# Chạy Redis với file config
CMD ["redis-server", "/usr/local/etc/redis/redis.conf"]