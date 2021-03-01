## About The Project

Docker compose app stack that makes up my fully automated htpc mediacenter.

### App list

I will attempt to keep this up to date.

- Proxy services
  - [traefik](https://hub.docker.com/_/traefik)
  - [traefik-custom-error-pages](https://hub.docker.com/r/guillaumebriday/traefik-custom-error-pages)
  - [cloudflare-companion](https://hub.docker.com/r/tiredofit/traefik-cloudflare-companion)
- Front end services
  - [organizr](https://hub.docker.com/r/organizr/organizr)
  - [plex](https://hub.docker.com/r/linuxserver/plex)
  - [tautulli](https://hub.docker.com/r/linuxserver/tautulli)
  - [overseerr](https://hub.docker.com/r/hotio/overseerr)
- Indexers
  - [sonarr](https://hub.docker.com/r/hotio/sonarr)
  - [radarr](https://hub.docker.com/r/hotio/radarr)
- Download clients
  - [nzbget](https://hub.docker.com/r/hotio/nzbget)
- Other
  - [tdarr-v2](https://hub.docker.com/r/haveagitgat/tdarr)
  - [radarr-collections](https://hub.docker.com/r/si0972/radarr-collections)
  - [watchtower](https://hub.docker.com/r/v2tec/watchtower)

## Getting Started

Before you are able to run these containers there are a few things that are going to need to be setup.

1. Copy sample.env to .env and fill out the fields to your need
