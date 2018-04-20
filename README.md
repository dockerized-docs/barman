# dockerized-docs-barman

# What is it? #
Dockerzied barman documentation for offline use.

# Image description #
- Base image: `centos/httpd-24-centos7`
- The http://docs.pgbarman.org/release/2.3/ site is mirrored using httrack

# How to use this image #

```console
$ docker run -d genadipost/barman
```

You can test it by visiting http://container-ip:8080

