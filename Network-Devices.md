
# Networking: Basic Concepts 

## 📌 Video Title
**Networking Fundamentals Overview**

## 🔗 Link
[Practical networking playlist](https://www.youtube.com/watch?v=bj-Yfakjllc&list=PLIFyRwBY_4bRLmKfP1KnZA6rZbRHtxmXi)

---

## 🧠 Key Concepts Covered
### 1. What is a Network?
- A network links devices for communication
- Defines how data travels
- Examples: LAN, WAN, Internet

### 2. OSI Model (High Level)
- Layer 1: Physical → bits & cables
- Layer 2: Data Link → MAC, Switches
- Layer 3: Network → IP, routing
- Layer 4: Transport → TCP/UDP
- Layers 5–7: Application (HTTP, DNS, etc.)

### 3. TCP/IP Model (Comparison)
- Link, Internet, Transport, Application
- Maps to OSI

---

## 🛠️ Useful Commands Mentioned

- `ip a` → display interfaces
- `ip r` → show routing table
- `ping <ip/host>` → check connectivity

---

## 📌 Definitions (simple)
- **IP Address:** Unique address to identify devices
- **MAC Address:** Hardware address
- **Router:** Routes between networks
- **Switch:** Connects devices in the same network

---

## 🧪 Practice / Labs
- Try pinging `localhost`, `127.0.0.1`
- Check network interfaces:
```bash
  ip a
```

- Try:

```bash
ping github.com
```
- Observe TTL / replies


## [[Hosts]]