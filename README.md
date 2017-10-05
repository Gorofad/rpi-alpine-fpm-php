# rpi-alpine-fpm-php
Alpine FPM PHP Docker image for Raspberry 

Usage
```Shell
sudo docker run -p 9000:9000 --name phpfpm -v /home/pi/public_html:/www:rw -d rpi-php
```

