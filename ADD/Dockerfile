FROM almalinux:9  
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/shahabsb94/Dockerfiles/refs/heads/main/COPY/Dockerfile /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]


# CMD --> to start the nginx server with out systemctl