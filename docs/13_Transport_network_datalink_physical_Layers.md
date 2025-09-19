# 13 - Transport, Network, Data Link, and Physical Layers

---

## Transport Layer
- Responsible for **process-to-process delivery** of the entire message.

### Services Offered
- **Port Addressing** – Uses port numbers to identify processes.  
- **Segmentation and Reassembly** – Splits large messages into smaller segments and reassembles them at the destination.  
- **Connection Control** – Can be **connection-oriented (TCP)** or **connectionless (UDP)**.  
- **End-to-End Flow Control** – Ensures sender does not overwhelm receiver.  
- **Error Control** – Ensures reliable delivery by retransmitting lost/erroneous segments.  

---

## Network Layer
- Responsible for **delivery of data** from the original source to the destination across networks.

### Services Offered
- **Logical Addressing** – Uses IP addresses for unique identification.  
- **Routing** – Finds the best path from source to destination.  

---

## Data Link Layer
- Responsible for moving **data frames** from one node to another node over a single link.

### Services Offered
- **Framing** – Divides stream of bits into manageable frames.  
- **Physical Addressing** – Adds MAC addresses to identify devices.  
- **Flow Control** – Prevents fast sender from overwhelming slow receiver.  
- **Error Control** – Detects and corrects errors at frame level.  
- **Access Control** – Decides which device has control over the shared medium.  

---

## Physical Layer
- Responsible for **transmitting raw bits** over a communication medium.  
- Defines **electrical, mechanical, and procedural specifications**.

### Services Offered
- **Characteristics of Media** – Specifies physical medium (cables, fiber, wireless).  
- **Representation of Bits** – Defines signal encoding (voltage levels, light pulses).  
- **Data Rate** – Number of bits transmitted per second.  
- **Synchronization of Bits** – Ensures sender and receiver are in sync.  
- **Line Configuration** – Point-to-Point or Multipoint connection.  
- **Physical Topology** – Defines arrangement of devices (Bus, Star, Ring, Mesh).  

---

✅ **Quick Mnemonic for Bottom 4 Layers:**  
**T**urtles **N**eed **D**eep **P**onds  
(Transport → Network → Data Link → Physical)
