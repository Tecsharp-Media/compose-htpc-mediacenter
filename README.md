## About The Project

Docker compose app stack that makes up my fully automated htpc mediacenter.

### App list

I will attempt to keep this up to date.

- Proxy services
  - [traefik](https://hub.docker.com/_/traefik)
  - [traefik-custom-error-pages](https://hub.docker.com/r/guillaumebriday/traefik-custom-error-pages)
  - [cloudflare-companion](https://hub.docker.com/r/tiredofit/traefik-cloudflare-companion)
- User identity & SSO
  - [authelia](https://hub.docker.com/r/authelia/authelia)
  - [keycloak](https://hub.docker.com/r/jboss/keycloak)
  - [openldap](https://hub.docker.com/r/osixia/openldap)
- Front end services
  - [organizr](https://hub.docker.com/r/organizr/organizr)
  - [emby](https://hub.docker.com/r/emby/embyserver)
  - [jellyfin](https://hub.docker.com/r/hotio/jellyfin)
  - [ombi](https://hub.docker.com/r/hotio/ombi)
- Indexers
  - [sonarr](https://hub.docker.com/r/hotio/sonarr)
  - [radarr](https://hub.docker.com/r/hotio/radarr)
- Download clients
  - [nzbget](https://hub.docker.com/r/hotio/nzbget)
- Databases
  - [mariadb](https://hub.docker.com/_/mariadb)
- Backed admin UI's
  - [phpldapadmin](https://hub.docker.com/r/osixia/phpldapadmin)
  - [phpmyadmin](https://hub.docker.com/_/phpmyadmin)
- Other
  - [watchtower](https://hub.docker.com/r/v2tec/watchtower)

## Getting Started

Before you are able to run these containers there are a few things that are going to need to be setup.

1. Copy sample.env to .env and fill out the fields to your need
2. In config/ombi there is a database.json file that will need to be copied to the secrets folder and filled in approperiatly
3. In config/authelia that will also need to be modified to your needs
4. In config/secrets there are example secrets you will need to copy all of the files in this folder to secrets, changing the secret passwords inthem to your need.
   - jwt
   - ldap
   - mysql
   - session
   - smtp
