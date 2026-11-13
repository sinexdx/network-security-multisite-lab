# Network Security – Multisite Network

## About

For this project, I used Cisco Packet Tracer to design and configure a network across three different locations: Dublin, London and Beijing.

The main aim was to improve the security of the network by implementing different security features to control access, protect devices and monitor network activity.

## Network Overview

The network included three sites:

- Dublin – Headquarters
- London – Data Centre
- Beijing – Home Office

Each location had its own network devices and LANs, which were configured to communicate with each other where required.

## What I Configured

Some of the main features I worked on included:

- Device hardening using enable secrets and password encryption.
- SSH to allow secure remote access to routers and switches.
- VLANs and OSPF routing.
- Port security and sticky MAC addresses to restrict devices connecting to switch ports.
- DHCP snooping to help prevent unauthorised DHCP servers.
- AAA and RADIUS for network authentication.
- Syslog to collect logs from network devices.
- WPA2 and AES encryption to secure the wireless network.
- Firewall rules and ACLs to control network traffic.
- NAT/PAT to translate private IP addresses.

I also attempted to configure an IPsec VPN between sites, but the tunnel was not successfully established.

## Testing

I carried out different tests to check that the configurations were working correctly. These included testing SSH access, checking port security, verifying Syslog messages, testing network connectivity and checking that ACLs were blocking traffic where required.

Most of the configurations were successfully tested. However, the IPsec VPN did not establish because the IKE negotiation was unsuccessful.

## Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI

## What I Learned

This project gave me practical experience configuring and securing a network. I learned how to use different security features, troubleshoot configurations and test whether network devices were communicating as expected.

**Project Type:** Academic Project  
**Module:** Network Security  
**Course:** Digital Forensics and Cybersecurity  
**Institution:** TU Dublin
