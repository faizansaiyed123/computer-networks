# 11 - OSI Reference Model

## Purpose
- The purpose of the **OSI Model** is to facilitate communication between different systems  
  **without requiring changes** to the logic of the underlying hardware and software.

---

## Layers in the OSI Reference Model (7 Layers)

1. **Application Layer**  
   - Provides services directly to the user.  
   - Examples: Email, Web Browsers, FTP.

2. **Presentation Layer**  
   - Ensures data is in a usable format.  
   - Handles **encryption, compression, and translation**.

3. **Session Layer**  
   - Manages **sessions** (start, maintain, end connections).  
   - Synchronizes dialog between systems.

4. **Transport Layer**  
   - Provides **end-to-end communication**.  
   - Ensures **reliability, error detection, and flow control**.  
   - Example protocols: TCP, UDP.

5. **Network Layer**  
   - Handles **routing and addressing** of data packets.  
   - Example protocols: IP, ICMP.

6. **Data Link Layer**  
   - Provides **error detection and correction** on a local link.  
   - Divided into **MAC (Media Access Control)** and **LLC (Logical Link Control)**.

7. **Physical Layer**  
   - Deals with the **physical medium** (cables, signals, voltages).  
   - Defines hardware specifications.

---

✅ **Tip to Remember:**  
**A**ll **P**eople **S**eem **T**o **N**eed **D**ata **P**rocessing  
(Application → Presentation → Session → Transport → Network → Data Link → Physical)
