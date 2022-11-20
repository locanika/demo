FROM nginx

RUN apt-get update && apt-get install -y \
  mc \
&& apt-get clean

WORKDIR /application

COPY ./nginx.conf /etc/nginx/conf.d/default.conf
