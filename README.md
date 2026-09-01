# 5-Node Virtualization & Home Infrastructure Cluster

## Overview
Engineered and deployed a 5-node Debian Linux home lab cluster managed via CasaOS. The architecture enforces strict workload isolation, fixed static IP routing, secure remote management, and real-time observability.

## Architecture & Workload Isolation
* **Node 1 (Media & Knowledge Base):** Immich, Jellyfin, Obsidian sync
* **Node 2 (Networking):** Network routing and traffic management
* **Node 3 (Security & Access):** Dedicated security tools and OpenVPN remote access
* **Node 4 (Observability):** Grafana metrics and system monitoring
* **Node 5 (Game Hosting):** Dedicated NeoForge Minecraft server

## Tech Stack
* **Operating System:** Debian Linux
* **Management UI:** CasaOS
* **Networking & Security:** Static IP Routing, OpenVPN
* **Monitoring:** Grafana
* **Applications:** Immich, Jellyfin, Obsidian, NeoForge
## Screenshots & Architecture Overview
### Physical Hardware Setup
![Physical Hardware Setup](20260708_144033.jpg)
### Cluster Setup & Dashboards
![Proxmox Cluster](./Screenshots%20for%205%20cluster%20Server/ProxmoxCluster.png)
![CasaOS Dashboard](./Screenshots%20for%205%20cluster%20Server/CasaOS.png)
![CasaOS Apps](./Screenshots%20for%205%20cluster%20Server/CasoOS%20Media%20App.png)

### Services & OS
![Debian Node](./Screenshots%20for%205%20cluster%20Server/Debain.png)
![Debian Screen](./Screenshots%20for%205%20cluster%20Server/DebianScreen.png)
![Obsidian Sync](./Screenshots%20for%205%20cluster%20Server/obsidian.png)
