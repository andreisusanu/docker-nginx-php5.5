[![](https://badge.imagelayers.io/andreisusanu/nginx-php5.5:latest.svg)](https://imagelayers.io/?images=andreisusanu/nginx-php5.5:latest)

nginx-php5.5
===========

Docker image for NGINX and PHP5.5, started using Supervisor.

Last stable NGINX installed from official stable repository (http://ppa.launchpad.net/nginx/stable/ubuntu)
Last PHP5.5 installed from Ondřej Surý's unofficial repository (http://ppa.launchpad.net/ondrej/php5/ubuntu)


Build
-----

```bash
docker build -t andreisusanu/nginx-php5.5 .
```


Run
-----
```bash
docker run \
    --name nginx-php5.5 \
    -p 80:80 \
    andreisusanu/nginx-php5.5
```