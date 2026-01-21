# At-Home Security Lab

## Overview
This repository documents the design and implementation of a personal at-home security lab built to develop hands-on experience in system administration, network security, and SOC/GRC fundamentals.

The lab focuses on **preventive controls, monitoring, automation, and incident-style investigation**, using low-cost hardware and production-style configuration practices.

---

## Architecture

**Devices**
- **Raspberry Pi 4 (“Gojo”)**
  - Linux monitoring and analysis node
  - Authentication log review
  - SOC-style investigation practice

- **Raspberry Pi Zero 2 W**
  - Dedicated DNS filtering appliance
  - Network-wide preventive security control

**High-Level Flow**

---

## Implemented Phases

### Phase 1 — Secure Baseline (Complete)
- Installed and hardened Raspberry Pi OS
- Removed default users and credentials
- Configured SSH and firewall rules
- Implemented static IP networking using NetworkManager

### Phase 1.5 — DNS Filtering & Automation (Complete)
- Deployed Pi-hole on a dedicated Raspberry Pi Zero 2 W
- Implemented network-wide DNS filtering
- Integrated automated blocklist updates using Firebog (low-risk lists)
- Scheduled weekly maintenance with cron
- Implemented logging for automated tasks

### Phase 2 — Monitoring & Log Analysis (In Progress)
- Performed authentication monitoring using systemd journal logs
- Identified and analyzed successful and failed SSH login attempts
- Practiced SOC-style event interpretation and risk assessment
- Preparing incident-style documentation and response workflows

---

## Skills Demonstrated
- Linux system administration
- Static IP networking
- DNS-based security controls
- Log monitoring and investigation
- Cron-based automation
- Preventive vs detective security controls
- SOC and GRC-aligned thinking

---

## Security Considerations
- No credentials, keys, or sensitive data are committed
- IP addresses are sanitized where documented
- Configurations are documented conceptually, not copied blindly

---

## Project Status
- Phase 1: ✅ Complete
- Phase 1.5: ✅ Complete
- Phase 2: 🚧 In progress

This repository will continue to evolve as additional monitoring, alerting, and documentation capabilities are added.
