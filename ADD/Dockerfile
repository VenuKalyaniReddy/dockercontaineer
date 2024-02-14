FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html
ADD https://raw.githubusercontent.com/daws-76s/notes/master/session-01.txt /tmp
## we can place the sample-2 in D/git/repo/devops/ADD
ADD sample-1 /tmp/
CMD ["nginx","-g","daemon off;"]



