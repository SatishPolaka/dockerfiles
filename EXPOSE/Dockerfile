FROM almalinux:9
RUN dnf install nginx -y
EXPOSE 80
ADD https://raw.githubusercontent.com/SatishPolaka/dockerfiles/refs/heads/main/FROM/Dockerfile /usr/share/nginx/html/index.html
EXPOSE 443
CMD ["nginx", "-g", "daemon off;"]