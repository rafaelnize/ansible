FROM nginx

RUN rm /etc/nginx/conf.d/default.conf

#RUN rm /etc/nginx/conf.d/examplessl.conf

COPY index.html /usr/share/nginx/html/

COPY default.conf /etc/nginx/conf.d/
