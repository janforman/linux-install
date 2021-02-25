# linux-server-install
Fast use - log in to server and run

```
wget https://github.com/janforman/linux-server-install/archive/main.zip -O /tmp/t.zip && unzip /tmp/t.zip -d /tmp && rm /tmp/t.zip && cd /tmp/linux-server-install-main/ && ./install.sh
```

* nginx + php
* mariadb
* scylladb
* mongodb
* wso2 microintegrator (mariadb, scylladb, mongodb, postgres, oracle connectors)
* mean stack (MongoDB, NodeJS)
* java openjdk
* docker
* phpmyadmin
* nextcloud

This script is intended to use in VPS (virtual server for single purpose in this case) and fresh OS install.

It's tested in UBUNTU Server 20.04.2 LTS
