# Dual ISP Failover and Load Balancing Using MikroTik Router

## Project Overview

This project focuses on the design and implementation of a Dual Internet Service Provider (ISP) Failover and Load Balancing System using a MikroTik Router.

The main objective is to improve network reliability, minimize Internet downtime, and optimize available bandwidth by using two independent Internet connections.

The system automatically switches to the secondary Internet connection when the primary connection fails and distributes network traffic across both connections to improve network performance.

## Objectives

- Design a network architecture using two Internet connections.
- Implement load balancing using MikroTik RouterOS.
- Configure automatic failover for network availability.
- Monitor Internet connectivity and link status.
- Evaluate network performance and reliability.

## Technologies and Tools

- MikroTik RouterOS
- MikroTik Winbox
- Per Connection Classifier (PCC)
- Netwatch
- Routing Marks
- Policy-Based Routing
- Static and Recursive Routing
- Network Monitoring Tools

## System Architecture

The system consists of:

- Primary Internet connection (MTN Rwanda).
- Secondary Internet connection (GMAX Ltd).
- MikroTik Router.
- Local Area Network (LAN).
- Connected client devices.

## Key Features

**1. Load Balancing:** Distributes network connections across two Internet providers.

**2. Automatic Failover:** Switches Internet traffic to the available connection when one link fails.

**3. Network Monitoring:** Monitors Internet connectivity and detects link failures.

**4. Improved Reliability:** Reduces Internet service interruptions.

## Implementation

The system was implemented using MikroTik RouterOS and configured through Winbox.

The implementation involved:
- Configuring both Internet connections.
- Setting up PCC load balancing.
- Configuring routing and failover mechanisms.
- Implementing Netwatch for connectivity monitoring.
- Testing network performance under different conditions.

## Performance Evaluation

The system was evaluated using:

- Internet availability.
- Failover response time.
- Packet loss.
- Network throughput.
- Load balancing performance.

## Project Outcomes

The project demonstrates how two Internet connections can be managed through a MikroTik router to improve network availability, reliability, and bandwidth utilization.

## Author

**Mahamat Sini Mahamat Saleh**

B-Tech – Electronic Telecommunications and Technology

## Project Type

Final Year Academic Project
