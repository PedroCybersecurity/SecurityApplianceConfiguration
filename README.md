# Security Appliance Configuration with pfSense

## Overview
This repository illustrates the successful configuration of a pfSense network security appliance as part of Lab 2.4.9 in TestOut CyberDefense Pro's English 2.0 course. The objective of this lab was to enhance the security of the corporate network by configuring DNS and a default gateway.

## Lab Tasks
- Sign in to pfSense using specific case-sensitive information.
- Configure the DNS servers with primary and secondary DNS settings.
- Configure the WAN IPv4 information.
- Add and configure a new default gateway.

## Implementation Details
- DNS Configuration:
  - Primary DNS server: 163.128.78.93 - Hostname: DNS1
  - Secondary DNS server: 163.128.80.93 - Hostname: DNS2

- WAN IPv4 Configuration:
  - Enable the interface.
  - Static IPv4 address: 65.86.24.136/8

- Default Gateway Configuration:
  - Type: Default gateway
  - Name: WANGateway
  - IP address: 65.86.1.1

## Lab Report
- Time Spent: 03:49
- Score: 3/3 (100%)

Feel free to explore this repository to understand how to configure DNS settings, WAN IPv4 information, and add a default gateway using pfSense for network security. This knowledge is valuable in the context of network security and administration.
