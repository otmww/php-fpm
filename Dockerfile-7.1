FROM ubuntu:16.04

ENV PROJECT_ROOT=/app \
    COMPOSER_HOME=/composer \
    COMPOSER_PROCESS_TIMEOUT=45 \
    COMPOSER_NO_INTERACTION=1 \
    COMPOSER_ALLOW_SUPERUSER=1

RUN apt-get update \
    && apt-get -qq -y install \
        ca-certificates \
        curl \
        wget \
        software-properties-common \
        python-software-properties \
    && LC_ALL=C.UTF-8 add-apt-repository ppa:ondrej/php \
    && apt-get update \
    && apt -qq -y install \
        php7.1 \
        php7.1-fpm \
        php7.1-opcache \
        php7.1-zip \
        php7.1-xmlrpc \
        php7.1-xsl \
        php7.1-mbstring \
        php7.1-mcrypt \
        php7.1-mysql \
        php7.1-odbc \
        php7.1-readline \
        php7.1-recode \
        php7.1-soap \
        php7.1-sqlite3 \
        php7.1-tidy \
        php7.1-xml \
        php7.1-json \
        php7.1-ldap \
        php7.1-intl \
        php7.1-imap \
        php7.1-gmp \
        php7.1-gd \
        php7.1-bz2 \
        php7.1-bcmath \
        php7.1-cgi \
        php7.1-cli \
        php7.1-curl \
        php7.1-pgsql \
        php-imagick \
    && ln -s /usr/sbin/php-fpm7.1 /usr/sbin/php-fpm \
    && rm -rf /var/lib/apt/lists/* /tmp/* \
    && mkdir $PROJECT_ROOT

COPY ./etc/ /etc/

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

ENV PATH "/composer/vendor/bin:$PATH:$PROJECT_ROOT/bin"

WORKDIR $PROJECT_ROOT

EXPOSE 9000

CMD ["php-fpm"]
