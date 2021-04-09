FROM oraclelinux:8
RUN dnf -y update && dnf -y module enable nginx:1.16 && dnf -y install nginx nginx-mod-http-perl gettext && rm -rf /var/cache/dnf
