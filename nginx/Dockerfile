FROM nginx:stable-alpine

COPY ./nginx/maintenance.html /usr/share/nginx/html

COPY ./nginx/default.conf /etc/nginx/conf.d

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]