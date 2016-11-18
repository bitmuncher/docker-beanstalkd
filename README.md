This repository contains build informations for a Docker image based on Debian with beanstalkd.

Run this image with:

```
docker run -d --name beanstalkd -v /var/beanstalkd:/var/beanstalkd -p 11300:1300 bitmuncher/beanstalkd
```


