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

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

- npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```

<!-- USAGE EXAMPLES -->

## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<!-- ROADMAP -->

## Roadmap

See the [open issues](https://github.com/github_username/repo_name/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- CONTACT -->

## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email

Project Link: [https://github.com/github_username/repo_name](https://github.com/github_username/repo_name)

<!-- ACKNOWLEDGEMENTS -->

## Acknowledgements

- []()
- []()
- []()

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/github_username
