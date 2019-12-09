# HTTPD Intergation Test Instance for TEST.GOKRB5

DO NOT USE THIS CONTAINER FOR ANY PRODUCTION USE!!!

To run:
```bash
docker run -v /etc/localtime:/etc/localtime:ro -p 80:80 -p 443:443 --rm --name gokrb5-http hashicorp/gokrb5:http &
```

To build:
```bash
docker build -t hashicorp/gokrb5:http --force-rm=true --rm=true .
docker push hashicorp/gokrb5:http
```


