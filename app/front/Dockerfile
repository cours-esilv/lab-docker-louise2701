
FROM nginx:alpine
WORKDIR /app/front
COPY . /app/front

COPY entrypoint.sh /docker-entrypoint.sh


RUN chmod +x /docker-entrypoint.sh

EXPOSE 80


CMD ["/docker-entrypoint.sh"]
