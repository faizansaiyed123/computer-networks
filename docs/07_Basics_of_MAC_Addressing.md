# 07 — Basics of MAC Addressing

## What is a MAC Address?
- **MAC** stands for **Media Access Control**.  
- Every node in a LAN is identified using a **MAC address**.  
- Analogy:  
  - **IP Address** = Location of a person  
  - **MAC Address** = Name of a person  
- Also called **physical address** or **hardware address**.  
- **Unique** and **cannot be changed** (burned into hardware by manufacturer).  
- Represented in **hexadecimal**.  
- Example: `70-20-84-00-ED-FC` (48 bits).  
- Separators: **hyphen (-)**, **period (.)**, **colon (:)**  

---

## IP Address vs MAC Address

### IP Address
- Needed for communication.  
- **32 bits** (IPv4).  
- Represented in **decimal**.  
- Required by **routers** to forward data.  
- Example: `10.10.23.45`  

### MAC Address
- Needed for communication.  
- **48 bits**.  
- Represented in **hexadecimal**.  
- Required by **switches** to forward data.  
- Example: `70-20-84-00-ED-FC`  

---

## How to View MAC Address on Real Devices
- On Windows:  
  ```bash
  ipconfig /all
