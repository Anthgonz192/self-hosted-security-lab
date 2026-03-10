# self-hosted-security-lab
Self-hosted cybersecurity homelab with Docker services, reverse proxy, monitoring, and security tooling.
# Self-Hosted Security Monitoring Homelab

## Overview

This project documents my self-hosted cybersecurity homelab built on Linux using Docker containers.  
The environment was created to practice infrastructure management, service monitoring, and security tooling similar to real-world SOC environments.

## Infrastructure

The homelab runs on a Raspberry Pi and hosts multiple containerized services.

Key components include:

- Docker containerized services
- Reverse proxy for secure service access
- Service uptime monitoring
- Security log monitoring
- Self-hosted applications

## Technologies Used

- Linux
- Docker
- Nginx Proxy Manager
- Wazuh
- OpenSearch
- Uptime Kuma
- Cloudflare DNS

## Security Concepts Practiced

- Reverse proxy configuration
- Network service exposure management
- Log monitoring and analysis
- Service availability monitoring
- Containerized infrastructure deployment

## Example Services

| Service | Purpose |
|------|------|
| Wazuh | Security monitoring and SIEM |
| OpenSearch | Log storage and analysis |
| Uptime Kuma | Service monitoring |
| Nginx Proxy Manager | Reverse proxy for web services |
| Ghost | Self-hosted blog platform |

## Screenshots

Screenshots of the environment are included in the `/screenshots` folder.

## Future Improvements

- Automated log alerting
- Intrusion detection integration
- Additional security monitoring tools
