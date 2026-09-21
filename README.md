# Termux Network Intelligence Toolkit

Scan your Wi‑Fi network, discover all connected devices, detect open ports, and generate a beautiful HTML report, all from your Android phone running Termux. No root required.

## Features
- Ping sweep to find live hosts
- Hostname resolution
- Common port scanning (21,22,23,80,443,445,8080,3306,3389)
- Generates HTML report saved to `/sdcard/network_report.html`
- Works offline, no cloud

## Quick Start
```bash
pkg install python nmap -y
git clone https://github.com/folorunsogeorge-dot/folorunsogeorge-dot.git
cd folorunsogeorge-dot
python net_scan.py
