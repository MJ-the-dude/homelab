# My HomeLab project 

## About this project
```
A homelab project aimed to develop and demonstrate platform engineering skills across the full production toolchain, plus have a lot of fun while doing so.

Being built as a self-directed learning path toward a potential role change to Platform Engineering / DevOps.
Started: June 2025. Heavily WIP.

All infrastructure is designed, broken, fixed, and documented by me.
Questions, feedback, or suggestions: open an issue.
```

---

## Architecture (WIP)

```
=====================================================
|   ISP Router <===> MikroTik <===> lab-daddy(M70q) |
|        ||                                         |
|        ||                                         |
|     Admin PC                                      |
=====================================================
```

---

## Hardware

| Device | Role | Key specs |
| -------- | -------- | -------- |
| Lenovo ThinkCentre M70q | Main lab server (lab-daddy)   |  i5-11500T · 16 GB DDR4 · 256 GB NVMe  |
| MikroTik hEX RB750Gr3 | Lab router | Dual-Core, 4 Threads CPU · 256 MB RAM · 5x 10/100/1000 Mbps | 

---

## Stack

| Layer | Technology |
| OS | Ubuntu Server 24.04 LTS |
| Networking | MikroTik RouterOS · VLANs |

