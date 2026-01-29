# Homelab Documentation

## Overview
Provide a high-level description of this homelab project. Include:
- Goals and purpose (learning, media, private services, K3s experimentation)
- Philosophy / design approach (e.g., separating critical vs replaceable data)
- How this project can evolve over time

---

## Hardware
Describe the hardware for each machine in simple paragraphs. Include CPU, RAM, GPU, and storage slots.
- **PC1 – Asus**
  - Example: Intel Core i5-4460 CPU, 4 cores, 16 GB RAM, NVIDIA GTX 960 GPU, 500 GB SSD system disk, 3x SATA expansion slots
- **PC2 – Dell PowerEdge T410**
  - Include RAID disks, controllers, RAM, CPU, GPU (if any)

---

## Network
Document your network design:
- VLAN layout
- pfSense VM placement
- IP addressing schema
- Routing rules / firewall strategy
- Notes for K3s cluster networking if needed

---

## Storage
Document your storage architecture:
- Disk layout per PC
- RAID / ZFS pools
- Backup strategy
- Where private vs replaceable data will reside
- Notes on planned future upgrades

---

## Cluster / K3s
Document your Kubernetes setup:
- Node roles (controller/worker)
- Where each node is located (PC1, PC2)
- App deployment strategy (which workloads run where)
- Notes on high availability or failover

---

## Applications
List all apps/services you plan to run, with notes for each:
- Media (Jellyfin, music servers)
- ARR stack (Sonarr, Radarr, etc.)
- Admin / monitoring tools (Grafana, Prometheus)
- Private services (Vaultwarden, Immich)
- Any additional tools or experimental setups

---

## Progress / Lessons Learned
Keep a running log of your work:
- Problems encountered and solutions
- Lessons learned or improvements
- Links to more detailed logs in `progress/` folder, e.g.:
  - [Network setup](progress/network.md)
  - [Storage setup](progress/storage.md)
  - [Cluster setup](progress/k3s.md)
  - [App deployments](progress/apps.md)

---

## Diagrams
Include reference diagrams to illustrate your architecture:
- Network topology
- Storage layout
- K3s cluster and app placement
- Store images in `/diagrams` folder and link them here
