FROM chialab/php:7.2
MAINTAINER dev@chialab.it

# Install XDebug.
RUN pecl install xdebug-beta \
    && echo "zend_extension=\"$(php-config --extension-dir)/xdebug.so\"" > $PHP_INI_DIR/conf.d/xdebug.ini
