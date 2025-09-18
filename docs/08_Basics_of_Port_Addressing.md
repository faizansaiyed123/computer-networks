# 08 — Basics of Port Addressing
 
## Analogy
- Reaching the **apartment building** = Reaching the host (IP address).  
- Reaching the **apartment unit** = Reaching the device (MAC address).  
- Reaching the **right person inside** = Reaching the correct process (Port address).  

---

## What is a Port Address?
- A **port address (port number)** uniquely identifies processes/services on a device.  
- Since many processes run on a node, the port ensures that data reaches the **right process**.  
- A port is a **communication endpoint**.  
- Range: **0 – 65535**  

---

## Types of Port Numbers
- **Well-known (Fixed) Ports** → `0 – 1023`  
  - Commonly used by standard services.  
  - Examples:  
    - `25` → SMTP (Email)  
    - `80` → HTTP (Web)  
- **Dynamic (Ephemeral) Ports** → `49152 – 65535` (assigned by OS for temporary use)  
  - Example: `62414`  

---

## How to View Port Numbers on a Real Device
- On Windows (open Command Prompt):  
  ```bash
  netstat -an
