FROM docker.io/redhat/ubi9
RUN dnf install nginx -y
RUN rm -rf /usr/share/mginx/html/*
COPY index.html /usr/share/mginx/html/index.html
