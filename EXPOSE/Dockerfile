FROM almalinux:9
RUN dnf install nginx -y
# there is no functionaly for expose it is just for information
EXPOSE 80
CMD [ "njinx", "-g", "daemon off;" ]

## build
## docker inspect expose:1.0.0