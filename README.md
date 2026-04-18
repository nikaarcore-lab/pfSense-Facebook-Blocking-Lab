# pfSense Facebook Blocking Lab

## Overview
This lab demonstrates how to block access to Facebook using pfSense firewall and DNS filtering (pfBlockerNG).

## Tools Used
- pfSense
- pfBlockerNG
- VirtualBox
- Windows 10 VM

## What I Did
- Installed and configured pfBlockerNG
- Created firewall alias for Facebook domains
- Configured firewall rules to block traffic
- Set up DNSBL filtering
- Flushed DNS cache on Windows
- Verified blocking result

## Result
Facebook access was successfully blocked. The browser returns a timeout error, confirming that traffic is filtered.

## Screenshots

### Lab environment
![Lab environment](Lab environment (VirtualBox + Windows + pfSense).png)

### pfSense dashboard
![Dashboard](pfSense dashboard.png)

### Firewall alias (Facebook domains)
![Alias](Firewall alias for Facebook blocking.png)

### Firewall rule
![Firewall rule](Firewall rules with Facebook block rule.png)

### DNSBL configuration
![DNSBL](pfBlockerNG DNSBL configuration.png)

### Reset firewall states
![Reset states](Reset firewall states.png)

### Flush DNS cache
![DNS flush](DNS cache flush on Windows.png)

### Blocked result
![Blocked](Facebook blocked (connection timeout).png)

## Skills Gained
- Firewall configuration
- DNS filtering (DNSBL)
- Network troubleshooting
- Traffic control using pfSense
