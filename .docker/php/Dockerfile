FROM php:7.3-fpm-alpine

# Use the default production configuration
RUN mv "$PHP_INI_DIR/php.ini-production" "$PHP_INI_DIR/php.ini"

# Override with custom opcache settings
# COPY config/opcache.ini $PHP_INI_DIR/conf.d/