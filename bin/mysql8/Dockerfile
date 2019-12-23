FROM mysql:8
RUN echo "default-authentication-plugin=mysql_native_password" >> /etc/mysql/my.cnf

ARG USER=${USER}
ENV USER=${USER}
ARG GROUP=${GROUP}
ENV GROUP=${GROUP}
RUN adduser --disabled-password --gecos '' $USER