#if we will not mention :8(version) it will install latest version of centos
FROM almalinux
RUN yum install nginx -y
RUN echo "Hello everyone,we are here for building our own image by using dockerfile" > /usr/share/nginx/html/hello.html
CMD [ "nginx", "-g", "daemon off;" ]