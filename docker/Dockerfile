FROM ubuntu:latest
MAINTAINER trg78
RUN apt update
RUN apt -y install nginx && apt -y install python
ADD ./nginx.conf /etc/nginx/
EXPOSE 80
CMD ["nginx", "tail -f /dev/null"]
