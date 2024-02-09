FROM nginx:alpine

COPY . /usr/share/nginx/html


ENV WS_BACK_URL=http://backend-service:5000/


EXPOSE 80


ENTRYPOINT ["nginx", "-g", "daemon off;"]