# homelab (see [r/homelab](https://www.reddit.com/r/homelab/))

This repository contains the Docker configurations and setup for my personal home server.

## Directory Structure

- `portainer-compose.yaml` - Portainer container management setup
- `backup/` - Backup services
- `media/` - Media management and streaming services
- `network/` - Reverse proxy, DNS, and dynamic DNS services

## [Portainer](https://github.com/portainer/portainer)

Portainer is used for managing and monitoring all Docker containers and services across the server. It provides a web-based interface for container management, image management, and stack orchestration. See `portainer-compose.yaml` for the Portainer setup.

## [Cup](https://github.com/sergi0g/cup)

A lightweight service that periodically scans my Docker images for new versions so that my containers stay up to date. See `portainer-compose.yaml` for the Cup setup.

## [Homepage](https://github.com/gethomepage/homepage)

A customizable home page dashboard that displays shortcuts to all my services and monitored stats. See `portainer-compose.yaml` for the Homepage setup.

## Server Hardware

- **CPU**: Intel N150
- **GPU**: Intel UHD Graphics 730
- **RAM**: 12GB
- **Storage**: 512GB internal SSD + 2 x 12TB HDD in RAID 1
- **OS**: Linux Mint
