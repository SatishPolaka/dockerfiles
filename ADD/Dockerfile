FROM almalinux:9
RUN dnf install nginx -y
ADD https://raw.githubusercontent.com/SatishPolaka/dockerfiles/refs/heads/main/FROM/Dockerfile /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]