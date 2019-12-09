# KDC Intergation Test Instance for RESDOM.GOKRB5

DO NOT USE THIS CONTAINER FOR ANY PRODUCTION USE!!!

To run:
```bash
docker run -v /etc/localtime:/etc/localtime:ro -p 188:88 -p 188:88/udp --rm --name gokrb5-res hashicorp/gokrb5:kdc-resdom &
```

To build:
```bash
docker build -t hashicorp/gokrb5:kdc-resdom --force-rm=true --rm=true .
docker push hashicorp/gokrb5:kdc-resdom
```


