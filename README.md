# 5-Node Virtualization & Home Infrastructure Cluster

## Overview
Engineered and deployed a 5-node Debian Linux home lab cluster managed via CasaOS running on Proxmox VE. The architecture enforces strict workload isolation, fixed static IP routing, secure remote management, and real-time observability.

## Server Goals & Architecture
My goal with this server environment is to expand my knowledge in infrastructure deployment, virtualization, security, and access management. Workloads are distributed across five dedicated physical nodes to ensure service isolation:

* **Server 1 (Personal/Home Services):** Jellyfin (media streaming), Obsidian (knowledge base), and Immich (photo backups)
* **Server 2 (Security Monitoring):** Grafana for real-time telemetry and metrics visualization
* **Server 3 (Network & Security):** OpenVPN for secure remote network access
* **Server 4 (Web Hosting):** Personal website hosting environment
* **Server 5 (Game Hosting):** High-performance NeoForge Minecraft server

## Hardware Specifications

| Node | Model | CPU | RAM | Storage |
| :--- | :--- | :--- | :--- | :--- |
| **Server 1** | HP EliteDesk 800 G1 DM | Intel Core i5-4590T @ 2.00GHz | 8GB | 500GB HDD |
| **Server 2** | HP EliteDesk 800 G1 DM | Intel Core i5-4590T @ 2.00GHz | 8GB | 500GB HDD |
| **Server 3** | Lenovo ThinkCentre M93p | Intel Core i5-4570 @ 3.20GHz | 16GB | 500GB HDD |
| **Server 4** | Lenovo ThinkCentre M93p | Intel Core i5-4570 @ 3.20GHz | 16GB | 500GB HDD |
| **Server 5** | Lenovo ThinkCentre M93p | Intel Core i5-4570 @ 3.20GHz | 16GB | 500GB HDD / 128GB SSD |

## Tech Stack
* **Hypervisor & OS:** Proxmox VE 9.2, Debian 13.6
* **Management UI:** CasaOS
* **Networking & Security:** OpenVPN, Static IP Routing
* **Monitoring:** Grafana
* **Hosted Applications:** Immich, Jellyfin, Obsidian, NeoForge Minecraft Server
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
