# Homelab

## Overview

This repository documents my personal homelab project, where I design, deploy, and manage a home server infrastructure using Proxmox, Kubernetes (K3s), and various services. The goal is to create a flexible and scalable environment for learning, testing, and showcasing practical DevOps and system administration skills.

The project focuses on:

- Virtualization and container orchestration  
- Network segmentation with VLANs and firewalls  
- Storage management with ZFS and RAID  
- Deploying applications like media servers, admin dashboards, and self-hosted tools  
- Experimentation, documentation, and process tracking  

Here you can find the main file describing plan of the homelab:

  - [Main File](docs/homelab.md)

---

## Folder Structure

---
homelab/

├── docs/

├── diagrams/

├── scripts/ 

├── experiments/ 

├── media/ 

├── README.md 

└── .gitignore 

---

## Documentation Approach

- **docs/** contains structured documentation for networking, storage, Kubernetes, deployed apps, backups, and lessons learned.  
- **diagrams/** shows network topology, VLAN assignments, and storage layouts.  
- **scripts/** stores reusable scripts and manifests to automate tasks.  
- **experiments/** is for testing and learning, later summarized in docs.  
- **media/** contains images and screenshots to support explanations.

Documentation is updated **regularly** during experiments, deployments, and troubleshooting to reflect progress and reasoning.

---

## Goals

1. Build a home server infrastructure that is **resilient, flexible, and scalable**.  
2. Learn and demonstrate practical **DevOps, networking, and storage skills**.  
3. Maintain detailed documentation to showcase **critical thinking and problem-solving**.  
4. Use this repository as a **portfolio for recruiters** and as a foundation for future engineering projects.

---

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/yourusername/homelab.git
cd homelab
