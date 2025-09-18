# 05 — Network Topology

## What is Network Topology?
Network topology is the **arrangement of nodes** in a computer network.  

- **Physical Topology** → Placement of various nodes (how devices are physically connected).  
- **Logical Topology** → Deals with data flow in the network (how data moves between devices).  

---

## 1. Bus Topology
- All nodes share a common transmission medium.  
- Data is broadcast to all nodes; only the intended recipient accepts it.  
- Signal travels in both directions until the recipient is found.  

**Advantages**
- Requires only one main cable → cost effective.  
- Suitable for temporary networks.  
- Node failure does not affect others.  

**Disadvantages**
- Not fault tolerant (no redundancy).  
- Limited cable length.  
- Poor security (data is visible to all).  

---

## 2. Ring Topology
- Similar to bus but forms a **closed loop**.  
- Each node is connected to two neighbors.  
- Data passes in **one direction** (unidirectional).  
- Uses a **token** to send/receive data.  

**Advantages**
- Performs better than bus under load.  
- Equal access for all nodes.  

**Disadvantages**
- Single point of failure affects the whole network.  
- Performance drops with heavy load.  
- Poor security.  

---

## 3. Star Topology
- Every node connects to a **central hub/switch**.  
- All communication passes through the hub/switch.  
- Centralized management.  

**Advantages**
- Easy to design and implement.  
- Centralized administration.  
- Scalable (easy to add/remove devices).  

**Disadvantages**
- Single point of failure (hub/switch).  
- Bottleneck at central hub/switch.  
- Higher cost (requires hub/switch).  

---

## 4. Mesh Topology
- Each node connects directly to every other node.  
- Provides redundancy and fault tolerance.  

**Advantages**
- Highly reliable and fault tolerant.  
- No single point of failure.  

**Disadvantages**
- Expensive (requires many cables/connections).  
- Impractical for large networks.  
- Broadcast traffic can cause issues.  

---
