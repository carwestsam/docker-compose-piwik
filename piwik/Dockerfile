FROM ubuntu:16.04
RUN apt-get update 
RUN apt-get install -y wget zip
RUN wget https://builds.piwik.org/piwik.zip
RUN unzip piwik.zip
RUN apt-get install -y php7.0 php7.0-curl php7.0-gd php7.0-cli php7.0-mysql php-xml php7.0-mbstring
EXPOSE 8000
CMD cd /piwik && php -S 0.0.0.0:8000


