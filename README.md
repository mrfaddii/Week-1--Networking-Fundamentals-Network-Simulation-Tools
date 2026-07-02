# Week 1 — Networking Fundamentals & Network Simulation Tools

**Internship:** Network Administration Internship Program
**Organization:** IT-SIMPLERA Institute
**Intern:** Muhammad Fahad Khan
**Supervisor:** Jawad Qayum (Senior Network Administrator)
**Week:** 01
**Date:** 2 July 2026

## Overview

This repository contains my Week 1 submission for the Network Administration Internship at IT-SIMPLERA Institute. The task focused on building a strong foundation in core networking concepts and gaining hands-on experience with two industry-standard network simulation tools: **Cisco Packet Tracer** and **GNS3**.

A simple Local Area Network (LAN) topology was designed and implemented in both platforms, with static IP addressing configured and end-to-end connectivity verified using the `ping` command.

## Objectives

- Understand fundamental networking concepts: network devices, IP addressing, and communication models
- Install, configure, and explore Cisco Packet Tracer and GNS3
- Design and implement a simple LAN topology in both platforms
- Configure static IP addressing and verify connectivity using `ping`
- Practice technical documentation and reporting

## Tools Used

- **Cisco Packet Tracer** — network simulation and topology design
- **GNS3** — network emulation using real device images
- **PuTTY** — terminal/console access for device configuration

## Repository Structure

```
Week-1--Networking-Fundamentals-Network-Simulation-Tools
├── README.md                 
├── Week1_Report.docx                
├── PacketTracer/
│   └── Network_Fundamentals_&_Network_Simulation_tools.pkt     
├── GNS3/
│   └── Network_Fundamentals_&_Network_Simulation_Tools.gns3        
└── Screenshots/
    ├── Cisco_Interface.png
    ├── Cisco_PC1_IP.png
    ├── Cisco_PC2_IP.png
    ├── Cisco_PC1_Ping.png
    ├── Cisco_PC2_Ping.png
    ├── GNS3_Interface.png
    ├── GNS3_PC1_IP.png
    ├── GNS3_PC2_IP.png
    ├── GNS3_PC1_Ping.png
    └── GNS3_PC2_Ping.png
    
```

## Topology Summary

- 2 Pcs connected to a swaitch
- IP for PC1 192.168.1.20
- IP for PC2 192.168.1.30
- Default gateway: 255.255.255.0


## Connectivity Testing

Static IP addresses were assigned to all end devices, and connectivity was verified using `ping` between:

- PC1 to Switch (gateway)
- PC2 to Switch (gateway)

  All the ping tests returned 0% packet loss with successful replies in both Cisco Packet Tracer and GNS3


## Key Learnings

- To understand about switches
- How static IP addressing, subnet masks, and default gateways work together
- Practical use of the `ping` command for connectivity troubleshooting
- Hands-on navigation of the Packet Tracer and GNS3 interfaces
- Differences between simulation (Packet Tracer) and emulation (GNS3) environments

## Challenges Faced

I’m new to GNS3 so I did face some challenges, I was trying to connect both the PCs and switch through wires but was facing some issue so I asked it from ChatGPT and it give me a solution with that I was able to complete my assignment without any difficulties. While I was already familiar with Cisco Packet Tracer so I did not face any difficulties completing the assignment.

## Related Links

- **LinkedIn Post:** https://www.linkedin.com/posts/qazi-muhammad-fahad-a59ab6415_week-1-ugcPost-7478433245903306754-NINI/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAGm0MWUBaXBVY-JUyCvHI6QMqh9YVTbldKE
- **Full Report:** See [`Week1_Report`](./Report.docx) in this repository

## Acknowledgements

Thank you to **IT-SIMPLERA Institute**, CEO of the IT_SIMPLERA Institute "Zia Ullah" and my supervisor, **Jawad Qayum** for the guidance and structure provided during this first week of the internship.
