#TODO search {{ registry-host }} for most lightweight latest stable _fixed_ nginx version
FROM nginx:1.20-alpine
EXPOSE 80
RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf.template /etc/nginx/templates/
ENV NGINX_BACKEND_HOSTNAME=backend
