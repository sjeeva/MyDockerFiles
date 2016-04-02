FROM ubuntu

MAINTAINER Jeeva

RUN apt-get uppdate && \
    apt-get -y apache2 php5 libapache2-mod-php5 && \
    apt-get clean
    
# Launch apache2 server in the foreground
ENTRYPOINT ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
