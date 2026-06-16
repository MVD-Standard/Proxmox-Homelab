# proxmox-homelab
Proxmox Homelab IT/Security Environment
# Proxmox Homelab - Self Hosted Cloud Infrastructure

## Overview

This project is a self-hosted cloud infrastructure environment built using Proxmox Virtual Environment on repurposed hardware. The goal of this project was to gain hands-on experience with virtualization, Linux administration, containerization, networking, and cybersecurity principles.

The homelab hosts multiple services through virtual machines and Docker containers while implementing security practices based on least privilege and zero-trust concepts.

---

# Architecture

## Hardware

* Repurposed desktop computer
* 8GB RAM
* Proxmox Virtual Environment hypervisor

## Virtualization

* Proxmox VE
* Ubuntu Server 24.04 LTS Virtual Machine

## Services

### Nextcloud

Self-hosted cloud storage platform deployed using Docker Compose.

### Docker

Used for containerized application deployment and service management.

### Nginx Proxy Manager

Implemented as a reverse proxy to manage application routing and SSL certificates.

### Tailscale VPN

Used for secure remote access without exposing services directly to the public internet.

---

# Security Implementations

Security practices implemented:

* Disabled root SSH login
* Created non-root administrative users
* Enabled sudo-based privilege escalation
* Configured Proxmox firewall rules
* Applied network segmentation principles
* Used Tailscale for encrypted remote access
* Managed services through controlled access points

---

# Skills Demonstrated

## Infrastructure

* Linux administration
* Virtual machines
* Proxmox virtualization
* Server management

## Cloud / DevOps

* Docker
* Docker Compose
* Service deployment
* Reverse proxy configuration

## Cybersecurity

* Firewall configuration
* Access control
* Least privilege principles
* Secure remote access
* System hardening

## Networking

* IP configuration
* VPN networking
* DNS concepts
* Service exposure management

---

# Challenges & Troubleshooting

During development, I resolved issues involving:

* Proxmox firewall blocking web interface access
* Docker Compose configuration errors
* Nextcloud database connectivity issues
* SSL certificate and reverse proxy configuration
* Trusted domain configuration

---

# Future Improvements

Planned additions:

* Centralized logging with a SIEM solution
* Monitoring dashboard
* Automated backups
* Additional security testing
* Infrastructure documentation
* Cloud deployment comparison

---

# Project Status

Current services are operational and accessible through secure remote access.

This project is continuously updated as new infrastructure and cybersecurity concepts are learned.
