# docker-nginx-letsencrypt-ombi

Deploy [Ombi](https://ombi.io/) via Docker Compose with an Nginx proxy and Let's Encrypt for HTTPS.

This project could be easily modified to host just about any site.

<p align="right">(<a href="#top">back to top</a>)</p>



## Getting Started

A few things are required before getting started:

### Prerequisites

* A Linux host with Docker and Docker Compose
* An email address to use for registartion with Let's Encrypt
* A publicly reachable domain name for Ombi

### Deployment

Clone the repo

```
git clone https://github.com/rnwood13/docker-nginx-letsencrypt-ombi.git
```

Navigate to the repo then copy or create a `.env` file and fill in with your information

```
cd docker-nginx-letsencrypt-ombi/
cp .env.sample .env
```

And deploy

```
docker-compose up -d
```

<p align="right">(<a href="#top">back to top</a>)</p>


## Image Versions

Here are some links to help you find available image versions to use in the `.env` file.

* [Nginx](https://hub.docker.com/_/nginx?tab=tags)
* [nginx-proxy/docker-gen](https://github.com/nginx-proxy/docker-gen/releases)
* [nginx-proxy/acme-companion](https://github.com/nginx-proxy/acme-companion/releases)
* [Ombi](https://github.com/Ombi-app/Ombi/releases)

<p align="right">(<a href="#top">back to top</a>)</p>


## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

## Credit

Shout out to:

* evertramos's [nginx-proxy-automation](https://github.com/evertramos/nginx-proxy-automation) project
* willquill's [plex-docker](https://github.com/willquill/plex-docker) repo

<p align="right">(<a href="#top">back to top</a>)</p>
