# Home-Networking-And-Firewalls

### How a network actually works: IP, DNS, NAT, routing, VLANs, and a firewall configured deliberately rather than by default.

![Chain K](https://img.shields.io/badge/Chain%20K-64748B?style=for-the-badge) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue?style=for-the-badge)](LICENSE-GPL) [![License: AGPL v3](https://img.shields.io/badge/License-AGPLv3-blue?style=for-the-badge)](LICENSE-AGPL)

[📖 Lesson Plan](docs/LESSON_PLAN.md) · [🎮 Interactive Tour](docs/interactive/index.html)

<!-- SCREENSHOT PLACEHOLDER: docs/screenshots/overview.png -->

> ⬜ **Scaffold pending.** Directory created to portfolio standard; full content (README, lesson plan, tour + quiz, skeleton code) still to be built. Part of **Chain K — Hardware & Systems Foundations**.

## Why This Was Built

Networking is the layer most developers treat as someone else's problem right up until something can't
connect. I want the model — how a packet gets from my laptop to a server and back, what NAT is really doing,
why DNS is involved in so many outages.

Configuring a firewall on my own network makes it concrete: deciding what's allowed rather than accepting a
default, segmenting devices I don't fully trust, and seeing exactly what a rule blocks.

## Why This Matters (Industry Application)

Networking knowledge is essential for backend, cloud, and security work, and it's the difference between
guessing at a connectivity problem and diagnosing it. Cloud networking (VPCs, subnets, security groups) is
the same concepts renamed, so this transfers directly.

## Topics Covered

| Area | What this project covers |
|------|--------------------------|
| IP & subnets | Addressing, CIDR, and what a subnet mask means |
| DNS | Resolution, records, caching, and common failure modes |
| NAT & routing | How private networks reach the internet |
| VLANs | Segmenting a network and why isolation matters |
| Firewalls | Default-deny, rules, and stateful inspection |
| Diagnostics | ping, traceroute, dig, netstat, and reading them |

## How This Connects

Chain K (Hardware & Tinkering). Foundation for **VPN-Deep-Dive-And-Simulator** and much of **Chain L**; mirrors cloud networking in **Chain J**.

---
Dual licensed — [GPL v3](LICENSE-GPL) and [AGPL v3](LICENSE-AGPL).
