FROM almalinux:9
RUN dnf install nginx -y
LABEL maintainer="Satish Polaka"
LABEL description="This is a custom Nginx image"
ADD https://raw.githubusercontent.com/SatishPolaka/dockerfiles/refs/heads/main/FROM/Dockerfile /usr/share/nginx/html/index.html
LABEL version="1.0"
LABEL nginx run contineously
CMD ["nginx", "-g", "daemon off;"]