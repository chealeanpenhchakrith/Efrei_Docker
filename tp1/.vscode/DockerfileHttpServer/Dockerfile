FROM nginx:alpine
RUN apk add --no-cache gettext

COPY nginx.conf /etc/nginx/templates/nginx.template

CMD ["/bin/sh", "-c", "envsubst < /etc/nginx/templates/nginx.template > /etc/nginx/conf.d/default.conf && exec nginx -g 'daemon off;'"]