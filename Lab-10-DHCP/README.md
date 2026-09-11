# Lab 10 - DHCP Configuration

## Course Information

- **Course:** Computer Networks
- **Course Code:** CSCL3209
- **Program:** Bachelor of Science in Artificial Intelligence
- **Semester:** 4th Semester
- **Student Name:** Anzal Azam Shaikh
- **Roll Number:** 24108106
- **Class:** BSAI 4A

---

## Objective

The objective of this lab is to configure Dynamic Host Configuration Protocol (DHCP) on a router and automatically assign IP addresses to devices in different networks.

---

## Tool Used

- Cisco Packet Tracer

---

## Network Topology

The network topology consists of:

- 1 Router
- 2 Switches
- Multiple PCs
- Laptops

Two different networks were configured:

- BSAI-4A
- BSAI-4B

The router was used to configure DHCP pools and automatically assign IP addresses to the connected devices.

---

## DHCP Configuration

### DHCP Pool 1 - BSAI-4A

The DHCP pool for the BSAI-4A network was configured with the following network address and default gateway:


ip dhcp pool BSAI-4A
network 192.168.10.0 255.255.255.0
default-router 192.168.10.1


DHCP Pool 2 - BSAI-4B

The DHCP pool for the BSAI-4B network was configured with the following network address and default gateway:

ip dhcp pool BSAI-4B
network 10.0.0.0 255.255.255.0
default-router 10.0.0.1
Tasks Performed
1. Network Topology Creation

A network topology was created in Cisco Packet Tracer using one router, two switches, PCs, and laptops.

2. DHCP Pool Configuration

Two DHCP pools were configured on the router:

BSAI-4A
BSAI-4B

Each DHCP pool was configured with its respective network address and default gateway.

3. Automatic IP Address Assignment

The PCs and laptops were configured to obtain IP addresses automatically using DHCP.

The devices sent DHCP requests and received IP addresses from the configured DHCP pools.

4. DHCP Verification

The IP configuration of the devices was checked to verify whether DHCP had successfully assigned IP addresses.

Successful DHCP requests were observed on the configured devices.

5. Connectivity Testing

Network connectivity was tested using the ping command.

The following gateway address was tested:

ping 192.168.10.1

This test was performed to verify communication between the device and the network gateway.

Screenshots

The Screenshots folder contains the following screenshots:

1. Network Topology

Shows the complete network topology with:

Router
Two switches
PCs
Laptops
BSAI-4A network
BSAI-4B network
2. DHCP Pool Configuration

Shows the configuration of the following DHCP pools:

BSAI-4A
BSAI-4B
3. DHCP IP Assignment

Shows devices receiving IP addresses automatically through DHCP.

4. Device IP Configuration

Shows the IP configuration of PCs and laptops after DHCP configuration.

5. Connectivity Test

Shows the ping test performed to verify connectivity with the gateway address:

192.168.10.1
Learning Outcomes

After completing this lab, I learned how to:

Create a network topology using Cisco Packet Tracer.
Configure DHCP on a router.
Create multiple DHCP pools.
Configure different IP networks.
Configure default gateways.
Automatically assign IP addresses to devices.
Verify DHCP IP assignment.
Check device IP configuration.
Test network connectivity using the ping command.
Repository Structure
Lab-10-DHCP
│
├── README.md
│
└── Screenshots
    ├── 01-Network-Topology.png
    ├── 02-DHCP-Pool-Configuration.png
    ├── 03-DHCP-IP-Assignment-PC0-Laptop0.png
    ├── 04-PC1-IP-Configuration.png
    ├── 05-PC2-IP-Configuration.png
    └── 06-Ping-Test-192.168.10.1.png
