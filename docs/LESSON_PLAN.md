# 📖 Lesson Plan — Home-Networking-And-Firewalls

> **Chain K — Hardware & Systems Foundations** | How a network actually works: IP, DNS, NAT, routing, VLANs, and a firewall configured deliberately rather than by default.

## What This Project Is

Build an accurate model of how a packet travels, then configure a firewall and network segmentation deliberately rather than by default.

## Learning Objectives

By the end I can:

1. Explain IP addressing, subnets, and CIDR notation.
2. Trace DNS resolution and diagnose common DNS failures.
3. Explain what NAT does and why private networks need it.
4. Segment a network with VLANs and justify the isolation.
5. Write **default-deny** firewall rules and understand stateful inspection.
6. Diagnose connectivity with ping, traceroute, dig, and netstat.

## Software You Will Use

- A configurable router (OpenWrt / pfSense / OPNsense).
- Wireshark for packet inspection.
- Standard network CLI tools.

## Build Order

1. Map your own network: devices, addresses, subnets.
2. Trace a DNS lookup end to end with dig.
3. Capture traffic in Wireshark and follow one connection.
4. Write default-deny firewall rules and open only what is needed.
5. Segment untrusted devices onto their own VLAN.
6. Break connectivity deliberately and diagnose it methodically.

## Common Mistakes to Avoid

- Default-allow rules that make the firewall decorative.
- Assuming NAT is a security control.
- Ignoring DNS when diagnosing 'the internet is down'.
- Putting IoT devices on the same network as everything else.
- Changing rules remotely and locking yourself out.

## Check Your Understanding

The quiz covers subnetting, DNS resolution order, NAT, stateful firewalls, and diagnostic tooling.

## Why This Matters (Industry Application)

Networking knowledge is essential for backend, cloud, and security work, and it's the difference between
guessing at a connectivity problem and diagnosing it. Cloud networking (VPCs, subnets, security groups) is
the same concepts renamed, so this transfers directly.

## Reflection Questions

- Which devices on your network do you actually trust, and does your configuration reflect that?
- How do these concepts map onto cloud VPCs and security groups?
