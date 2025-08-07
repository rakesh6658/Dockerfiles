FROM almalinux
EXPOSE 80
RUN yum install nginx -y
RUN echo "welcome to docker" > /usr/share/nginx/html/rakesh.html
CMD ["nginx","-g","daemon off;"]

