# homelab

This repository contains the Docker Compose configurations and setup for my personal home server.

## Directory Structure

- `portainer-compose.yaml` - Portainer container management setup
- `dns/` - DNS server and ad blocking services
- `media/` - Media management and streaming services
- `proxy/` - Reverse proxy and SSL certificate management

## [Portainer](https://github.com/portainer/portainer)

Portainer is used for managing and monitoring all Docker containers and services across the server. It provides a web-based interface for container management, image management, and stack orchestration. See `portainer-compose.yaml` for the Portainer setup.

## Server Hardware


- **CPU**: Intel Twin-Lake N150
- **RAM**: 12GB
- **Storage**: 2 x 12TB Seagate IronWolf HDD - RAID 1
- **OS**: Linux Mint
