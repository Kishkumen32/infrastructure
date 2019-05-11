FROM redis:latest

ENV REDIS_PASSWORD abc123

CMD ["sh", "-c", "exec redis-server --requirepass \"$REDIS_PASSWORD\""]