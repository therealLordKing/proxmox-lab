# proxmox-lab
# Proxmox Homelab – Public Build Log

This repository documents my first Proxmox VE homelab build from scratch.

This is **not** a polished tutorial or a best-practice guide.  
It’s a real build log focused on what breaks, why it breaks, and how I fix it.

The goal is to learn publicly and create realistic lab environments that reflect what you’d see in real-world networks.

---

## Project Status
**Current stage:** Pre-install  
- Proxmox ISO downloaded  
- Bootable USB not created yet  
- Installation not started

This repo will be updated incrementally as the build progresses.

---

## Why Proxmox
Proxmox VE is a type-one hypervisor, meaning it runs directly on bare metal instead of on top of another operating system.

This allows:
- Multiple virtual machines on a single physical host
- Better performance and isolation
- More realistic lab environments

I’ve installed Proxmox once before and ran into networking issues, so part of the focus here will be understanding and fixing those problems properly.

---

## Hardware
This machine was previously my daily driver and is now being repurposed as a dedicated Proxmox node.

- CPU: Intel i7 (9th gen)
- RAM: 64 GB
- Storage: TBD
- Network: Wired Ethernet (direct connection planned)

This hardware is overkill and you don't need this - an old laptop is fine. I am using it for learning purposes so resource constraints don’t limit experimentation.


---

## What This Lab Is For
This lab will be used to:
- Build and break virtualized environments
- Practice different network topologies
- Simulate real-world scenarios
- Learn and explain concepts through hands-on testing

I’ll be running multiple virtual machines with different roles and network configurations as the lab evolves.

---

## This Lab Is *Not*
- Not a production environment  
- Not client infrastructure  
- Not a step-by-step beginner guide (yet)  

Configs, IPs, and examples are going to be sanitized and anything sensitive stays private.

---

## Documentation Style
Notes in this repo are going to be:
- Practical
- Concise
- Focused on mistakes and fixes

Expect:
- Raw install steps
- Troubleshooting notes
- Lessons learned
- Incremental progress

A polished version will come later, if at all. I will likley leave this repo as is and make a new one if I decide to clean it up. 

---

## Repo Structure (planned)


proxmox-lab/
├─ README.md
├─ install/
│ ├─ 01-hardware-prep.md
│ ├─ 02-proxmox-install.md
│ ├─ 03-network-setup.md
│ └─ screenshots/
├─ issues/
│ └─ common-problems.md
├─ notes/
│ └─ daily-log.md
└─ resources.md

This structure may evolve as the lab grows.

---

## Related Content
This lab is part of a public build series:
- YouTube: walkthroughs and context
- X: progress updates, issues, and lessons learned

Links are included in the video descriptions and posts.

---

## Disclaimer
This repo reflects my learning process at a specific point in time.  
If something is incorrect or incomplete, it will be updated as I learn more.

If you’re building something similar and run into the same issues, I hope these notes help.
