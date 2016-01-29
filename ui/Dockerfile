FROM nginx:latest

MAINTAINER tim.rodger@gmail.com

EXPOSE 80

CMD ["nginx"]

# Move application files into place
COPY src/ /home/app/

# Install server configuration
COPY build/nginx.conf /etc/nginx/
