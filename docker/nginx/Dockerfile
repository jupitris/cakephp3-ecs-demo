FROM nginx:latest
ARG APP_ENV

ADD ./docker/nginx/default.conf.${APP_ENV} /etc/nginx/conf.d/default.conf

ADD . /var/www/html
