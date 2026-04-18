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

## Lab environment
<img src="Lab environment (VirtualBox + Windows + pfSense).png" width="700"/>

## pfSense dashboard
<img src="pfSense dashboard.png" width="700"/>

## Firewall alias (Facebook domains)
<img src="Firewall alias for Facebook blocking.png" width="700"/>

## Firewall rule
<img src="Firewall rules with Facebook block rule.png" width="700"/>

## DNSBL configuration
<img src="pfBlockerNG DNSBL configuration.png" width="700"/>

## Reset firewall states
<img src="Reset firewall states.png" width="700"/>

## Flush DNS cache
<img src="DNS cache flush on Windows.png" width="700"/>

## Blocked result
<img src="Facebook blocked (connection timeout).png" width="700"/> 

## Skills Gained
- Firewall configuration
- DNS filtering (DNSBL)
- Network troubleshooting
- Traffic control using pfSense
