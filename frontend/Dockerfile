FROM nginx:latest

RUN rm /etc/nginx/conf.d/*

COPY nginx.conf /etc/nginx/conf.d/default.conf
 
COPY . /var/www/app

EXPOSE 80
