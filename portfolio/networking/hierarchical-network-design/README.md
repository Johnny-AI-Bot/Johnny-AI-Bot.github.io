# Hierarchical Network Design

This project demonstrates the design and implementation of a hierarchical enterprise network model using the Core, Distribution, and Access layer architecture.

The objective of this project is to model a scalable, manageable, and secure enterprise network that follows industry best practices for performance, fault isolation, and network growth.

---

## Network Architecture

The network is structured using the three-layer hierarchical model:

### Core Layer
- High-speed backbone responsible for fast and reliable data transport
- Optimized for low latency and high availability
- No policy enforcement to maintain performance

### Distribution Layer
- Acts as a policy boundary between access and core layers
- Handles routing between VLANs
- Implements access control and network segmentation

### Access Layer
- Provides end-device connectivity
- VLAN-based segmentation for departments
- Supports endpoint security and traffic isolation

---

## Key Concepts Demonstrated

- Hierarchical network design (Core / Distribution / Access)
- VLAN segmentation and logical separation
- Inter-VLAN routing
- Scalable enterprise network architecture
- Fault isolation and simplified troubleshooting

---

## Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI
- Enterprise switching and routing concepts

---

## Files

- `hierarchical-network-design.pkt` – Packet Tracer implementation of the hierarchical enterprise network topology

