FROM nginx:1.13.12

# ADD sites-enabled/ /etc/nginx/sites-enabled

# VOLUME ["/etc/nginx/sites-enabled", "/etc/nginx/certs", "/etc/nginx/conf.d", "/var/log/nginx", "/var/www/html"]

WORKDIR /etc/nginx

EXPOSE 80
EXPOSE 443

CMD ["nginx"]
