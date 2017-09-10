FROM phpstorm/php-71-apache-xdebug

MAINTAINER holy4god <hu2008yinxiang@163.com>

RUN curl -O https://codeload.github.com/phalcon/cphalcon/tar.gz/v3.2.1
RUN tar xvzf v3.2.1
RUN cd cphalcon-3.2.1/build && ./install
RUN cd ../../ && rm -Rf cphalcon-3.2.1 && rm -Rf v3.2.1
RUN docker-php-ext-enable phalcon