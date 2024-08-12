# i am the author of this image
FROM almalinux:9
RUN dnf install -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD [ "nginx", "g", "deamon off;" ]
