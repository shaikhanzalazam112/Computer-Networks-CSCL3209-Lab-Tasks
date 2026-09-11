# Lab 11 - Configuration of Static Routing

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

The objective of this lab is to understand and perform Static Routing using Cisco Packet Tracer and enable communication between different networks.

---

## Tool Used

- Cisco Packet Tracer

---

## Exercise

### Task 1: Static Routing Configuration

Static Routing was performed on the given network topology.

Different network addresses were used instead of the networks provided in the lab manual.

The following requirements were followed:

- Performed Static Routing on the given topology.
- Used different networks from those used in the lab manual.
- Mentioned the roll number on the routers.
- Added a tag with the student name and roll number.
- Tested communication within the network.
- Tested communication outside the network.

---

## Static Routing

Static Routing is a routing method in which routes are manually configured on routers.

The network administrator manually specifies the path that packets should follow to reach a destination network.

---

## Tasks Performed

### 1. Network Topology Creation

A network topology was created in Cisco Packet Tracer using the required network devices.

The topology was configured according to the requirements of the lab experiment.

---

### 2. Network Address Configuration

Different network addresses were used for the topology instead of the networks provided in the lab manual.

IP addresses were configured on the required network devices.

---

### 3. Router Identification

The roll number was mentioned on the routers as required in the lab instructions.

A tag containing the student name and roll number was also added to the network topology.

**Student Name:** Anzal Azam Shaikh

**Roll Number:** 24108106

---

### 4. Static Route Configuration

Static routes were manually configured on the routers to enable communication between different networks.

The basic format of a Static Route command is:


ip route destination-network subnet-mask next-hop-address

Static routes allow the router to forward packets to networks that are not directly connected.

5. Ping Within the Network

Connectivity was tested between devices within the same network.

The ping test was performed to verify successful communication between devices.

6. Ping Outside the Network

Connectivity was also tested between devices located on different networks.

Static Routing was configured to allow packets to travel from one network to another network.


!! Why is There a Need for Routing Protocols?

Routing protocols are needed because they:

Automatically discover the best paths.
Handle network changes dynamically.
Reduce manual configuration.
Improve scalability.
Ensure reliability in large networks.
Difference Between Static and Dynamic Routing
Feature	Static Routing	Dynamic Routing
Configuration	Manual	Automatic
Updates	No	Yes
Scalability	Low	High
Complexity	Simple	Complex
Network Size	Small	Large
Advantages of Static Routing
Simple to configure.
More secure.
Suitable for small networks.
Disadvantages of Static Routing
Does not automatically update routes.
Requires manual configuration.
Not suitable for large networks.
Advantages of Dynamic Routing
Automatically discovers routes.
Automatically handles network changes.
More scalable.
Suitable for large networks.
Disadvantages of Dynamic Routing
Uses more network and router resources.
More complex than Static Routing.
Concept of Hop Count in Routing


!!! Hop Count is the number of routers a packet passes through to reach its destination.

Example
PC → Router → Router → PC

Hop Count = 2

Key Points
Hop Count is used as a routing metric.
A lower hop count represents a preferred route.
Each router passed by a packet counts as one hop.
Screenshots


The Screenshots folder contains screenshots related to:

Network Topology
Router Configuration
Static Route Configuration
Ping Within the Network
Ping Outside the Network
Learning Outcomes

After completing this lab, I learned how to:

Understand the concept of Static Routing.
Create a network topology using Cisco Packet Tracer.
Configure different IP networks.
Configure router interfaces.
Manually configure Static Routes.
Enable communication between different networks.
Test connectivity within a network.
Test connectivity outside a network.
Understand the need for Routing Protocols.
Differentiate between Static and Dynamic Routing.
Understand the advantages and disadvantages of Static and Dynamic Routing.
Understand the concept of Hop Count in Routing.


Repository Structure
Lab-11-Static-Routing
│
├── README.md
│
└── Screenshots
