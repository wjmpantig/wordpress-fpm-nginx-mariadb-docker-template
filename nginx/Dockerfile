FROM nginx:latest


COPY ./nginx.conf /etc/nginx/nginx.conf
# COPY ./localhost.conf /etc/nginx/sites-enabled/localhost.conf
COPY ./localhost.conf /etc/nginx/conf.d/default.conf

# RUN echo "server_names_hash_bucket_size 64;" >> /etc/nginx/conf.d/default.conf
# RUN echo "client_max_body_size 12M;" >> /etc/nginx/conf.d/default.conf

WORKDIR /var/www/html/