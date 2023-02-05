# groovy-web-gradle-spring-jsf-traefik-reverse-proxy-hello-world

## Description
A springboot web app with jsf support.

Requests are routed through `traefik` rules.

## Tech stack
- groovy
  - springboot
  - jsf
- ssl
- proxy server

## Docker stack
- alpine
- traefik
- gradle:jdk11

## To run
`sudo ./install.sh -u`
- [Available at](https://myapi.docker.localhost)

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Traefik setup](https://medium.com/it-dead-inside/use-traefik-for-local-docker-https-4f3965d7d129)
