---
title: Nodes
---
flowchart TD
    A[Modem] -->|Disable WiFi| B(Mi 4A WAP cum switch)
    B --> C{Proxmox}
    C -->|VLAN 101| D[PfSense]
    C -->|VLAN 101| E[Photoprism]
    C -->|Three| F[fa:fa-hdd TrueNAS scale]
  