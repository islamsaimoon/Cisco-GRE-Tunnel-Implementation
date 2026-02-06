# Cisco-GRE-Tunnel-Implementation
Implementation of a Site-to-Site GRE Tunnel using Cisco 2911 routers to establish secure, point-to-point communication between remote office LANs

# Cisco Site-to-Site GRE Tunnel Implementation

This project demonstrates the configuration of a Generic Routing Encapsulation (GRE) tunnel to connect two geographically separated branch offices over a simulated WAN.

## 🛠 Network Topology & Tools
- **Routers:** 2x Cisco 2911 Routers
- **Protocols:** GRE (Generic Routing Encapsulation), ICMP, Static Routing
- **Software:** Cisco Packet Tracer

## 🚀 Technical Implementation
1. **Tunnel Interface Configuration:** Defined tunnel source and destination IPs on both edge routers.
2. **Encapsulation:** Used GRE to encapsulate private LAN traffic for traversal across the public WAN interface.
3. **Routing:** Configured static routes to direct traffic from `192.168.10.0/24` to `192.168.20.0/24` through the tunnel.
4. **Verification:**
   - **Ping Test:** Verified 0% packet loss between end-user hosts across the tunnel.
   - **Trace Route:** Confirmed that data traverses the virtual tunnel interface rather than the standard internet hop.

## 📸 Proof of Connectivity
PKT files and screenshots are provided!
