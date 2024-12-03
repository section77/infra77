# Infra77 

## Host
```
OS:     Debian
IP:     TBD
Hostname: TBD
```
## Description
This is a repository for the Infra77 project. The target to define the application configuration and Infrastructure As Code.

## Requirements
- Podman
- python3-pip
- podman-compose

## Tools
| Tool          | Host-Port      |
|---------------|----------------|
| Homeassistant | 8123           |
| Traefik       | 80 , 443, 8080 |
| *DNS-Server*  | 53              |
| wiki.js       |  |
| keycloak      ||
| Postgres      ||
| Watchtower    ||

## Manual testing

```bash
podman-compose --env-file ~/infra77/data/creds.env -f ~/infra77/compose-files/traefik.yml up
```

## Deployment Strategy

TBD