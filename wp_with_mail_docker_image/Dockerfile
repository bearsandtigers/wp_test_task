FROM wordpress:4.7.1-php7.0-fpm

RUN apt update ;\
    apt install -y -q --no-install-recommends \
		ssmtp \ 
    && apt-get clean \
    && rm -r /var/lib/apt/lists/*
