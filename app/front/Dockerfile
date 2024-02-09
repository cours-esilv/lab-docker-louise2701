
FROM nginx:alpine


WORKDIR /app/front


COPY . /app/front

COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh

EXPOSE 80

CMD ["/entrypoint.sh"]
