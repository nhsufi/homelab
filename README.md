# homelab (see [r/homelab](https://www.reddit.com/r/homelab/))

This repository contains the Docker configurations and setup for my personal home server.

## Directory Structure

- `portainer-compose.yaml` - Portainer container management setup
- `backup/` - Backup services
- `dns/` - DNS server and ad blocking services
- `media/` - Media management and streaming services
- `proxy/` - Reverse proxy and SSL certificate management

## [Portainer](https://github.com/portainer/portainer)

Portainer is used for managing and monitoring all Docker containers and services across the server. It provides a web-based interface for container management, image management, and stack orchestration. See `portainer-compose.yaml` for the Portainer setup.

## Server Hardware

- **CPU**: Intel N150
- **GPU**: Intel UHD Graphics 730
- **RAM**: 12GB
- **Storage**: 512GB internal SSD + 2 x 12TB HDD in RAID 1
- **OS**: Linux Mint
