# Lab 12 - Dynamic RIP Routing Protocol Configuration

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

The objective of this lab is to understand and perform the configuration of the Dynamic Routing Information Protocol (RIP) and enable communication between different networks.

---

## Tool Used

- Cisco Packet Tracer

---

## Exercise

### RIP Configuration

RIP configuration was performed on the given network topology.

The following instructions were followed:

- Used a different network from the one used in the lab manual.
- Configured Dynamic RIP Routing.
- Tested connectivity using PDUs.
- Tested connectivity using the Command Prompt.
- Verified communication between different networks.

---

## What is RIP?

RIP stands for Routing Information Protocol.

It is a Dynamic Routing Protocol that automatically shares routing information between routers.

RIP uses Hop Count as its routing metric to determine the best path to a destination network.

---

## Tasks Performed

### 1. Network Topology Configuration

A network topology was configured in Cisco Packet Tracer using routers and end devices.

Different network addresses were used instead of the network addresses provided in the lab manual.

---

### 2. IP Address Configuration

IP addresses were configured on the required devices and router interfaces according to their respective networks.

---

### 3. RIP Configuration

RIP was configured on the routers to enable automatic route sharing between different networks.

Dynamic Routing allows routers to exchange routing information automatically.

---

### 4. Connectivity Testing Using PDUs

Network connectivity was tested using PDUs in Cisco Packet Tracer.

PDUs were used to verify whether packets could successfully travel between devices in different networks.

---

### 5. Connectivity Testing Using Command Prompt

Connectivity was also tested using the ping command through the Command Prompt.

The ping command was used to verify communication between devices and networks.

---

## Why Was RIP Configured?

Before configuring RIP, communication with devices outside the local network was not established.

RIP was configured to allow routers to dynamically exchange routing information and enable communication between different networks.

---

## Maximum Hop Count in RIP

The maximum hop count in RIP is **15 hops**.

A hop means the number of routers a packet passes through to reach its destination.

If a destination is **16 hops away or more**, RIP considers the destination unreachable.

---

## Effect of Hop Count on Network Size

The hop count limitation affects the size of networks that RIP can effectively manage.

- RIP supports a maximum of 15 hops.
- A destination with 16 or more hops is considered unreachable.
- RIP is suitable for small to medium-sized networks.
- RIP is not efficient for large or complex networks with many routers.

---

## Screenshots

The `Screenshots` folder contains screenshots related to:

1. Network Topology
2. IP Address Configuration
3. RIP Configuration
4. PDU Connectivity Testing
5. Command Prompt Ping Testing

---

## Learning Outcomes

After completing this lab, I learned how to:

- Understand the concept of Dynamic Routing.
- Understand the Routing Information Protocol (RIP).
- Configure RIP on routers.
- Configure different IP networks.
- Enable automatic route sharing between routers.
- Test connectivity using PDUs.
- Test connectivity using the Command Prompt.
- Understand the concept of Hop Count.
- Understand the maximum hop count limitation of RIP.
- Understand the effect of RIP hop count on network size.

---

```text
Lab-12-RIP-Routing
│
├── README.md
│
└── Screenshots
