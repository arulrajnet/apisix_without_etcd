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
