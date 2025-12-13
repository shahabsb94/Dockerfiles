FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/sahre/nginx/html/index.html
ONBUILD COPY index.html /usr/sahre/nginx/html/index.html
CMD [ "nginx", "-g", "daemon off;" ]
