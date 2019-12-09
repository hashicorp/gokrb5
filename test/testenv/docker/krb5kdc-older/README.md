# KDC Intergation Test Instance for TEST.GOKRB5

DO NOT USE THIS CONTAINER FOR ANY PRODUCTION USE!!!

To run:
```bash
docker run -v /etc/localtime:/etc/localtime:ro -p 78:88 -p 78:88/udp --rm --name gokrb5-kdc-older hashicorp/gokrb5:kdc-older &
```

To build:
```bash
docker build -t hashicorp/gokrb5:kdc-older --force-rm=true --rm=true .
docker push hashicorp/gokrb5:kdc-older
```