FROM nginx:1.10.1
# OSX file share issue

RUN mkdir -p /var/www/html
RUN usermod -u 1000 www-data


#Entry point script
#COPY entrypoint.sh /sbin/entrypoint.sh
#ONBUILD COPY /entrypoint.d/* /entrypoint.d/
#RUN chmod 755 /sbin/entrypoint.sh
#RUN chmod +x /sbin/entrypoint.sh
#ENTRYPOINT ["/sbin/entrypoint.sh"]