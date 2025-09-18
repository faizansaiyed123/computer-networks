# 06 — Basics of IP Addressing

## What is an IP Address?
- **IP** stands for **Internet Protocol**.  
- Every node in a computer network is identified using an **IP address**.  
- It is a **logical address** (not tied to hardware).  
- It can **change based on location** of the device.  
- Assigned **manually** (static) or **dynamically** (DHCP).  

---

## IPv4 Address
- Written in **decimal format** (four octets → `x.x.x.x`).  
- Range: **0.0.0.0 to 255.255.255.255** (32 bits).  
- Example: `192.168.1.1`  

---

## Checking IP Address on a Device
- On Windows:  
  1. Press `Win + R` → type `cmd` → press Enter.  
  2. Run:  
     ```bash
     ipconfig
     ```  
- On Linux/Mac:  
  ```bash
  ifconfig
