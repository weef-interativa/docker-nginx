FROM nginx:1.16-alpine

COPY default.conf /etc/nginx/conf.d/default.conf

EXPOSE 80

WORKDIR /etc/nginx

CMD ["nginx", "-g", "daemon off;"]