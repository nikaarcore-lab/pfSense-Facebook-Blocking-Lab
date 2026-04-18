# pfSense Facebook Blocking Lab

## Overview
This lab demonstrates how to block access to Facebook using pfSense firewall and DNS filtering (pfBlockerNG).

## Tools Used
- pfSense
- pfBlockerNG
- VirtualBox
- Windows 10 VM

## What I did
- Installed and configured pfBlockerNG
- Created firewall rules to block Facebook
- Configured DNSBL filtering
- Tested connectivity before and after blocking

## Result
Facebook access was successfully blocked. The browser returns a timeout error, confirming that traffic is filtered.

## Screenshots

### Blocked access
![Blocked](screenshots/blocked.png)

### Firewall rule
![Firewall](screenshots/firewall.png)

### pfBlockerNG setup
![Setup](screenshots/setup.png)

## 📚 Skills gained
- Firewall configuration
- DNS filtering
- Network troubleshooting
- Traffic control using pfSense
