## EJEMPLO BASE ##

# FROM ubuntu:18.04
# LABEL description="first docker file"
# LABEL version=1.0
# LABEL fechacreation=072820

# RUN apt-get update && apt-get install -y figlet

# RUN mkdir -p /tmp/testing/ && cd /tmp/testing/ && touch test1

# COPY index.html /tmp/testing/

## ULTIMO EJERCICIO ##

FROM nginx
LABEL description="httpd image"
LABEL version="1.0"
LABEL creationdate="073020"

COPY index.html /usr/share/nginx/html/

#VOLUME . /devops/www/
VOLUME /devops/www

EXPOSE 8080





# sudo su
# cat /root/.bash_history

# docker build -t <nombreimagen>:<tag> .

# docker run 

# /vagrant

