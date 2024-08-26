FROM nginx
RUN rm /etc/nginx/conf.d/default.conf
RUN mkdir -p /etc/letsencrypt/archive/www.birulaut.com
COPY ./nginx.conf /etc/nginx/nginx.conf
COPY ./hosts /etc/
COPY ./cert/cert1.pem /etc/letsencrypt/archive/www.birulaut.com/
COPY ./cert/chain1.pem /etc/letsencrypt/archive/www.birulaut.com/
COPY ./cert/fullchain1.pem /etc/letsencrypt/archive/www.birulaut.com/
COPY ./cert/privkey1.pem /etc/letsencrypt/archive/www.birulaut.com/
