FROM almalinux:9 
RUN dnf install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html  
ADD https://github.com/santhan29/dockerfiles/blob/main/CMD/Dockerfile /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"] 