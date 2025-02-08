# Networking - CS2CA17

This repository contains the coursework for the Computer Architecture & Networking module (CS2CA17) at the University of Reading, instructed by Professor Shuang-Hua Yang.

## Coursework Description
**Wireshark Packet Analysis:** Capturing and analyzing LAN and Remote ICMP data using Wireshark.

**Small Office Network Implementation:** Configuring a small office network using Packet Tracer, including DHCP, DNS, and HTTP server setups.

**DNS and HTTP Server Setup:** Creating a mapping between a website and the HTTP server to verify connectivity.

## Task 1: Wireshark Packet Analysis

- **Objective:** Capture and analyze LAN and Remote ICMP data in Wireshark.
- **Tools Required:** Wireshark
- **Details:**
  - Capture LAN IP addresses and analyze data.
  - Ping the website `www.reading.ac.uk` and examine the captured data.
  - Analyze and reflect on IP and MAC address information.

## Task 2: Small Office Network Implementation

- **Objective:** Configure a small office LAN with specified devices and servers.
- **Tools Required:** Packet Tracer
- **Details:**
  - Configure the following devices:
    - 5 PCs, 1 Printer, 1 Mobile, 1 Tablet PC connected to a wireless router.
  - IP Configuration:
    - Default Gateway: `192.168.1.1/24`
    - PC1: `192.168.1.10/24`
    - PC2: `192.168.1.11/24`
    - PC3: `192.168.1.12/24`
    - PC4: `192.168.1.13/24`
    - PC5: `192.168.1.14/24`
    - Printer: `192.168.1.253/24`
  - Wireless Router Configuration:
    - SSID: `pollyvacherwireless`
    - Security: WPA2 Enterprise AES with shared key `P0llyVch3r`
  - Test device-to-device connectivity.
  - Install and configure DNS and HTTP servers:
    - DNS Server: `192.168.1.2/24`
    - HTTP Server: `192.168.1.3/24`
  - Update DHCP configuration to reserve IP addresses for the new servers.
  - Test DNS resolution and HTTP access.

## Task 3: DNS and HTTP Server Setup

- **Objective:** Configure DNS and HTTP servers to ensure network connectivity.
- **Tools Required:** Packet Tracer
- **Details:**
  - Set up a DNS server with the IP address `192.168.1.2/24`.
  - Set up an HTTP server with the IP address `192.168.1.3/24`.
  - Configure the DNS server to map the domain `www.pollyvacher.ac.uk` to the HTTP server.
  - Test DNS resolution and HTTP access from various devices in the network.


