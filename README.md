# nextcloud-ansible

Full bootstrap of Nextcloud on a naked Debian Buster.

## Install components

- php-fpm
- nginx-full
- redis
- APCu
- mariadb
- collabora online

## Setup the system

**Please read carefully the comments in the Playbook!!!!1**

- Unix account for nextcloud
- Create database and acount in mariadb
- Enable Redis
- Setup php-fpm for the nextclod unix account
- Install Collabora Online
- Lets Encrypt Certificates with acme.sh
- Configure NGINX as webserver
- Issue TLS certificates via acme.sh
- Configure NextCloud after install
