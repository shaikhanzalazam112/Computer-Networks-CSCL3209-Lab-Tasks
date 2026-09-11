# Lab 09 - Router Console Configuration

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

The objective of this lab is to connect a PC to a router using a console connection and perform basic router configuration and security settings.

---

## Tool Used

- Cisco Packet Tracer

---

## Network Topology

The network topology consists of:

- 1 PC
- 1 Cisco 2811 Router
- Console Connection

The PC was connected to the router to access and configure the Router Command Line Interface (CLI).

---

## Tasks Performed

### 1. Router Console Connection

A PC was connected to the Cisco 2811 Router using a console connection.

This connection allowed direct access to the router configuration through the CLI.

---

### 2. Configure Console Password

A password was configured for console access.

The following commands were used:

```text
line console 0
password anzal1
login
3. Configure Enable Password

An enable password was configured to secure privileged EXEC mode.

enable password szabist1
4. Save Router Configuration

The router configuration was saved using:

copy running-config startup-config

The running configuration was successfully saved as the startup configuration.

5. Reload Router

The reload command was used to restart the router.

reload
Screenshots

The Screenshots folder contains:

1. PC to Router Console Connection

This screenshot shows the network topology with a PC connected to a Cisco 2811 Router.

2. Router Configuration and Passwords

This screenshot shows:

Console password configuration
Console login configuration
Enable password configuration
Saving the router configuration
Router reload command
Learning Outcomes

After completing this lab, I learned how to:

Connect a PC to a router using a console connection.
Access the Router CLI.
Configure a console password.
Configure an enable password.
Save the running configuration.
Reload a router.
Perform basic router security configuration.
