# Network Performance Testing Using Cisco Packet Tracer

## Overview
This focuses on measuring and analyzing network performance metrics such as latency, bandwidth, jitter, and packet loss using Cisco Packet Tracer. It provides hands-on experience with testing network performance, troubleshooting issues, and optimizing configurations.

## Objectives
- Set up a network topology in Cisco Packet Tracer.
- Measure latency and packet loss using **ping** and **traceroute**.
- Analyze bandwidth and jitter using the **Traffic Generator**.
- Capture and inspect network packets using **Packet Sniffer**.
- Optimize network performance based on test results.

## Requirements
- **Software**: Cisco Packet Tracer
- **Devices**: Two routers, two PCs (one client, one server)
- **Tools**: Ping, Traceroute, Traffic Generator, Packet Sniffer

## Setup
### Step 1: Create the Network Topology
1. Open **Cisco Packet Tracer**.
2. Add **two routers** and **two PCs**.
3. Connect the devices using **copper straight-through** or **cross-over** cables.
4. Assign **IP addresses**:
   - Router 1: `192.168.1.1/24` (PC 1) and `10.0.0.1/24` (Router 2)
   - Router 2: `192.168.2.1/24` (PC 2) and `10.0.0.2/24` (Router 1)
   - PC 1 (Client): `192.168.1.2/24`, Gateway: `192.168.1.1`
   - PC 2 (Server): `192.168.2.2/24`, Gateway: `192.168.2.1`

### Step 2: Verify Connectivity
- **Ping Test**: Run `ping 192.168.2.2` from PC 1 to check connectivity.
- **Troubleshoot** if necessary:
  - Verify IP configurations
  - Check cable connections
  - Ensure correct default gateways

## Tasks
### Task 1: Latency and Packet Loss Testing
- Use **Ping** to measure **round-trip time (RTT)** and packet loss.
- Use **Traceroute** to determine network path and latency at each hop.

### Task 2: Bandwidth and Jitter Testing
- Switch to **Simulation Mode**.
- Use **Traffic Generator** to create different traffic types (e.g., HTTP, FTP, VoIP).
- Observe bandwidth usage and jitter (packet delay variation).

### Task 3: Packet Analysis
- Use **Packet Sniffer** to capture network traffic.
- Analyze **RTT, jitter, packet retransmissions**.

---

## Author
This project was created by the repository owner.
