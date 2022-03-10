FROM joomla:3.7.3

COPY ./kickstart/* /var/temp/

ENTRYPOINT []
CMD /bin/bash -c "cp /var/temp/* /var/www/html/ && exec /entrypoint.sh apache2-foreground"
