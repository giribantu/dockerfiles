FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html

ADD https://raw.githubusercontent.com/giribantu/myrepo/refs/heads/main/17_07_resume_build%20and%20some%20links.txt /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]