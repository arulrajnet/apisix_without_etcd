APISix Without ETCD
===================

This is a simple example of how to use APISix without ETCD.

Refer the official documentation of the [APISix Standalone Mode](https://apisix.apache.org/docs/apisix/deployment-modes/#standalone)

## Prerequisites

- Docker
- Docker Compose

## How to run

```bash
docker-compose up -d
```

Then

To see upstreams proxied via apisix

http://localhost:9080/web1/

http://localhost:9080/web2/

The prometheus metrics URL is

http://localhost:9091/apisix/prometheus/metrics

## Author

<p align="center">
  <a href="https://x.com/arulrajnet">
    <img src="https://github.com/arulrajnet.png?size=100" alt="Arulraj V" width="100" height="100" style="border-radius: 50%;" class="avatar-user">
  </a>
  <br>
  <strong>Arul</strong>
  <br>
  <a href="https://x.com/arulrajnet">
    <img src="https://img.shields.io/badge/Follow-%40arulrajnet-1DA1F2?style=for-the-badge&logo=x&logoColor=white" alt="Follow @arulrajnet on X">
  </a>
  <a href="https://github.com/arulrajnet">
    <img src="https://img.shields.io/badge/GitHub-arulrajnet-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub @arulrajnet">
  </a>
  <a href="https://linkedin.com/in/arulrajnet">
    <img src="https://custom-icon-badges.demolab.com/badge/LinkedIn-arulrajnet-0A66C2?style=for-the-badge&logo=linkedin-white&logoColor=white" alt="LinkedIn @arulrajnet">
  </a>
</p>
