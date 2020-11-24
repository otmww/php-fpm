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
        php7.2 \
        php7.2-fpm \
        php7.2-opcache \
        php7.2-zip \
        php7.2-xmlrpc \
        php7.2-xsl \
        php7.2-mbstring \
        php7.2-mysql \
        php7.2-odbc \
        php7.2-readline \
        php7.2-recode \
        php7.2-soap \
        php7.2-sqlite3 \
        php7.2-tidy \
        php7.2-xml \
        php7.2-json \
        php7.2-ldap \
        php7.2-intl \
        php7.2-imap \
        php7.2-gmp \
        php7.2-gd \
        php7.2-bz2 \
        php7.2-bcmath \
        php7.2-cgi \
        php7.2-cli \
        php7.2-curl \
        php7.2-pgsql \
        ffmpeg \
        php-imagick \
    && ln -s /usr/sbin/php-fpm7.2 /usr/sbin/php-fpm \
    && rm -rf /var/lib/apt/lists/* /tmp/* \
    && mkdir $PROJECT_ROOT

COPY ./etc/ /etc/

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

ENV PATH "/composer/vendor/bin:$PATH:$PROJECT_ROOT/bin"

WORKDIR $PROJECT_ROOT

EXPOSE 9000

CMD ["php-fpm"]
