# rpi-alpine-fpm-php
Alpine FPM PHP Docker image for Raspberry 

Based on https://hub.docker.com/r/resin/raspberry-pi-alpine/

and https://github.com/docker-library/php 

Usage
```Shell
sudo docker run -p 9000:9000 --name phpfpm -v /home/pi/public_html:/www:rw -d rpi-php
```

