FROM chialab/php:7.1-fpm
MAINTAINER dev@chialab.it

# Install XDebug.
RUN pecl install xdebug \
    && echo "zend_extension=\"$(php-config --extension-dir)/xdebug.so\"" > $PHP_INI_DIR/conf.d/xdebug.ini
