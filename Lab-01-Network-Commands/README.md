# Lab 01 - Network Commands

## Course Information

**Course:** Computer Networks
**Course Code:** CSCL3209
**Program:** Bachelor of Science in Artificial Intelligence
**Semester:** 4th Semester
**Student Name:** Anzal Azam Shaikh
**Roll Number:** 24108106
**Class:** BSAI 4A

---

## Objective

The objective of this lab is to understand and use basic network commands for checking network configuration, testing connectivity, performing DNS lookups, and tracing network paths.

---

## Tasks Performed

### 1. IP Configuration

Command used:

```text
ipconfig /all
```

This command was used to check:

* IPv4 Address
* Subnet Mask
* Default Gateway
* Network Adapter Information

---

### 2. MAC Address

The MAC address of the network adapter was checked using:

```text
ipconfig /all
```

A MAC address is a unique physical address assigned to a network interface card (NIC).

---

### 3. Ping Default Gateway

The default gateway was pinged to test connectivity between the computer and the local network.

The following were observed:

* Round-trip time
* Packet loss

---

### 4. Ping Public Websites

The following websites were tested using the ping command:

```text
ping google.com
```

```text
ping facebook.com
```

The following information was observed:

* IP Address
* Round-trip time
* TTL value
* Packet loss

---

### 5. Ping Unreachable Host

A non-existent or unreachable IP address was pinged to observe network behavior.

Observation:

* No reply was received.
* Packets were lost.
* The host was unreachable or unavailable.

---

### 6. DNS Lookup

Command used:

```text
nslookup google.com
```

This command was used to find the IP address associated with the domain name.

The DNS response was also checked to determine whether it was authoritative or non-authoritative.

---

### 7. Reverse DNS Lookup

A reverse DNS lookup was performed using an IP address.

This was used to check whether the IP address could be resolved back to a domain name.

---

### 8. Traceroute

Command used:

```text
tracert google.com
```

This command was used to trace the path of packets from the local computer to the destination server.

The following information was observed:

* Number of hops
* Routers in the network path
* Routers that did not respond

---

## Commands Used

```text
ipconfig /all
ping <default-gateway>
ping google.com
ping facebook.com
nslookup google.com
nslookup <IP-address>
tracert google.com
```

---

## Screenshots

All screenshots of commands and outputs are available in the **Screenshots** folder.

---

## Learning Outcomes

After completing this lab, I learned how to:

* Check network configuration using `ipconfig /all`
* Identify IPv4 address, subnet mask, and default gateway
* Understand the purpose of a MAC address
* Test network connectivity using `ping`
* Check packet loss and response time
* Perform DNS lookups using `nslookup`
* Perform reverse DNS lookups
* Trace the path of packets using `tracert`

---

## Tools Used

* ## Tools Used

- Cisco Packet Tracer
