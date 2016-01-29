FROM nginx:latest

MAINTAINER tim.rodger@gmail.com

EXPOSE 80

CMD ["/home/app/run.sh"]

# Move application files into place
COPY src/ /home/app/

RUN chmod +x  /home/app/run.sh

#RUN rm /etc/nginx/conf.d/nginx.conf

# Install server configuration
COPY build/nginx.conf /etc/nginx/


#CMD ["nginx", "-g", "daemon off;"]