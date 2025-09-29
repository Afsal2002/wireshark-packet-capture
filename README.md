# wireshark-packet-capture
capturing the packets using wireshark



## 📌 Task
Capture, filter, and analyze network packets using **Wireshark** to understand different network protocols and their behavior.

---

## ⚡ Steps Performed

### 1. Start Capture
- Opened **Wireshark**.
- Selected the **active network interface** (Wi-Fi).
- Began packet capturing.

### 2. Generate Traffic
- Browsed a website (`github.com`) to generate HTTP traffic.
- Used `ping google.com` to create ICMP/DNS requests.

### 3. Stop Capture
- Stopped packet capture after approximately **1 minute**.

### 4. Filter Packets by Protocol
Applied the following filters:
- `http` → To view website traffic.  
- `dns` → To see domain resolution queries.  
- `tcp` → To analyze transport-level communication.  

### 5. Identify Protocols
Found at least **3 protocols** in the capture:
 **DNS** – Resolves domain names into IP addresses.
   <img width="1366" height="768" alt="Screenshot From 2025-09-29 10-24-11" src="https://github.com/user-attachments/assets/bd624ffd-2f81-4204-aaf0-fbef7b530536" />

 **HTTP** – Handles website communication.
   <img width="1366" height="768" alt="Screenshot From 2025-09-29 10-23-41" src="https://github.com/user-attachments/assets/e0e21f13-56a9-4df8-9205-7d5e267e9e90" />
 
 **TCP** – Ensures reliable data delivery.
<img width="1366" height="768" alt="Screenshot From 2025-09-29 10-24-30" src="https://github.com/user-attachments/assets/58dcd43b-0516-4346-88f3-4bac78085bd0" />

### 6. Export Capture
- Saved the capture as a `.pcap` file:  
  **File → Save As → Wireshark/tcpdump (.pcap)**  

---

## 🔍 Findings & Analysis
- **DNS Packets:** Showed queries for domains like `google.com`.  
- **HTTP Packets:** Contained requests and responses during web browsing.  
- **TCP Packets:** Displayed connection establishment (3-way handshake) and data transfer.  

👉 **Key Insight:** DNS resolves names → TCP establishes connection → HTTP transfers content.

---



---

## 📂 Output

- Tools used: **Wireshark**  

