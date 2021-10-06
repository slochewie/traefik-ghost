# Docker based Ghost CMS with Traefik

## Motivation

- host a publicly facing Ghost CMS with SSL ceertificates by Let's Encrypt
- run public maintained images with no modifications
- require minimal configuration and setup

## Features

- [Ghost CMS](https://ghost.org/) - The world's most popular modern publishing platform for creating a new media platform. Used by Apple, SkyNews, Buffer, OpenAI, and thousands more.
- [Mariadb](https://mariadb.org/) - MariaDB Server is one of the most popular open source relational databases. It's made by the original developers of MySQL and guaranteed to stay open source.
- [Netdata](https://www.netdata.cloud/) - Troubleshoot slowdowns and anomalies in your infrastructure with thousands of metrics, interactive visualizations, and insightful health alarms.
- [Traefik](https://traefik.io/) is a modern HTTP reverse proxy and load balancer that makes deploying microservices easy.

## Requirements

- dedicated server or PC
- [docker](https://docs.docker.com/install/linux/docker-ce/debian/) and [docker-compose](https://docs.docker.com/compose/install/#install-compose)
- domain with configurable sub-domains (eg. netdata.example.com)
