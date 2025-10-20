# MiniBot
homelab
**Work in Progress**

# Mini-Bot
Naming reason: "Due to their smaller size and often unassuming vehicle modes, Mini-Bots like Bumblebee were well-suited for scouting, infiltration, and gathering intelligence without being easily detected. Bumblebee, for instance, is described as having the best vision and energy efficiency among the Autobots and is capable of going underwater for reconnaissance."

This system is being picked as it will be low power consumption, but highly impactful for the home system. Mini will be used first and foremost for me to get more comfortable using other server software. [BEN's](https://github.com/g-i-n-g-y/B.E.N.) unRaid feels one rails which is nice for me first starting out. I am looking to explore more so this side project is what I have picked up. 

- Proxmox
- Immich
- VMs for testing/breaking/fixing before rolling out elsewhere. I've learned through mistakes test on scrap paper, VM, before actually pushing to laptop. I was trying to edit how my Linux Mint UI looked and ended up changing more than intended.


October 2025 plan update:
Looking into Kubernetes and how I can use it for my home lab.

Lenovo ThinkCentre M710q or M720q (i5-6500)
2×16 GB DDR4 SODIMM
500 GB SSD Boot Drive

Had AI suggest build out timeline:
Month 0–1	Build MiniBot Node #1 (Control Plane + VMs)
Month 2–3	Add Node #2 (Worker #1); deploy Immich + backups
Month 4–6	Add Node #3 (Worker #2); start scaling apps
Month 7–12	Add Node #4 (Worker #3); enable monitoring + replicas
Ongoing	Tune resources, update K3s, experiment with new service
