FROM kylemanna/openvpn
MAINTAINER Oleksii Dzhulai nixlike@gmail.com

ADD ovpn_initpki /usr/local/bin/ovpn_initpki
ADD ovpn_genconfig /usr/local/bin/ovpn_genconfig
RUN chmod 700 /usr/local/bin/ovpn_initpki
RUN chmod 700 /usr/local/bin/ovpn_genconfig
