---
title: Haris Edge repositories
description: Source repositories for Haris Edge, including marine-haris (the vessel edge stack) and Watchtower automation, both MIT licensed.
keywords:
  - Haris Edge repositories
  - marine-haris
  - Watchtower repository
  - maritime open source
---

# Repos

Haris Edge is a set of focused sub-projects, all released under the MIT licence.

## `marine-haris`

Python-based vessel edge stack covering parsers, transmission, health monitoring, hardware notes, deployment guides, and system services.

Repository: <https://github.com/project-haris/marine-haris>

## `watchtower`

Ansible automation for vessel edge devices and M-SOC core services, including Haris deployment, Tailscale, ELK, Node-RED, and supporting system roles.

Repository: <https://github.com/project-haris/watchtower>

### Roles managed for vessel-edge nodes

- `sysctl` - kernel and system tuning
- `users_groups` - local users and group management
- `sshd` - SSH server configuration
- `soft_apt` - Debian package installation baseline
- `mullvad_browser` - Mullvad Browser deployment
- `firewalld` - host firewall rules
- `resolv_hosts` - hostname and resolver entries
- `artis3n.tailscale.machine` - Tailscale client setup
- `cron` - scheduled task management
- `haris` - Haris collector and Signal K integration
- `nodered` - Node-RED installation and setup
- `chrony` - time synchronization
- `zabbix_agent` - node monitoring agent

### Roles managed for M-SOC core nodes

- `sysctl` - kernel and system tuning
- `users_groups` - local users and group management
- `sshd` - SSH server configuration
- `soft_yum` - RPM-based package installation baseline
- `firewalld` - host firewall rules
- `resolv_hosts` - hostname and resolver entries
- `artis3n.tailscale.machine` - Tailscale client setup
- `cron` - scheduled task management
- `chrony` - time synchronization
- `zabbix_agent` - node monitoring agent
- `zabbix_server` when enabled - central Zabbix server stack
- `elk_stack` when enabled - Elasticsearch, Logstash, and Kibana
- `docker` when enabled - container runtime installation

## `haris.oversight.ee`

This documentation site, built with Zensical and served at <https://haris.oversight.ee>. It documents Haris Edge, the open component; the Haris platform itself is proprietary and is described in [the platform page](platform.md).
