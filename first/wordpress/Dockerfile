FROM ihub/php-fpm:5.4

ADD init.sh /init.sh
RUN chmod +x /init.sh

ENTRYPOINT ["/init.sh", "/usr/bin/supervisord", "-n", "-c", "/etc/supervisord.conf"]
