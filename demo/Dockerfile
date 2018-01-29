FROM ubuntu:xenial

RUN apt update
RUN apt install -y nginx
RUN echo 'Ojete!!!!' > /usr/share/nginx/html/index.html
RUN echo 'Prueba 2' > /usr/share/nginx/html/caca.html
EXPOSE 80
CMD ["/usr/sbin/nginx", "-g", "daemon off;"]

