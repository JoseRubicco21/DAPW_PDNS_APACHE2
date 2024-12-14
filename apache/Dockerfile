FROM debian:12

RUN apt-get update && apt-get install -y apache2 php

EXPOSE 80
EXPOSE 443

ENTRYPOINT [ "apachectl", "-D", "FOREGROUND" ]