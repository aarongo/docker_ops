FROM nginx:stable-alpine

VOLUME /data/nginx


COPY nginx.conf /etc/nginx/nginx.conf
COPY upstream.conf /etc/nginx/conf.d/upstream.conf
COPY nginx.nexus.conf /etc/nginx/conf.d/nginx.nexus.conf