# Image
FROM nginx:1.18-alpine

# Add config
COPY ./nginx.conf /etc/nginx/nginx.conf
COPY ./default.conf /etc/nginx/conf.d/default.conf

# Proxy configurations
COPY ./includes/ /etc/nginx/includes/
