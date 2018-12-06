FROM nginx:alpine

ARG compute_engine=fargate

COPY config/$compute_engine.conf /etc/nginx/conf.d/

COPY html /var/www/html
