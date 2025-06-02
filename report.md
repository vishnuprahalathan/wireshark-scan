# 📡 Wireshark Packet Analysis Report

## 🧾 Protocols Observed

### 1. DNS (Domain Name System)
- **Purpose**: Resolves domain names to IP addresses.
- **Example Packet**:
  - Timestamp: 12.345678
  - Source: 192.168.0.10
  - Destination: 8.8.8.8
  - Port: 53 (UDP)
  - Info: Standard query 0x1234 A www.google.com

---

### 2. TCP (Transmission Control Protocol)
- **Purpose**: Reliable, ordered delivery of data across the network.
- **Example Packet**:
  - Timestamp: 25.483291
  - Source: 192.168.0.10
  - Destination: 142.250.80.110
  - Port: 443
  - Info: TCP segment with ACK and PSH flags

---

### 3. HTTP (HyperText Transfer Protocol)
- **Purpose**: Transfers web pages from servers to browsers.
- **Example Packet**:
  - Timestamp: 27.920043
  - Source: 192.168.0.10
  - Destination: 93.184.216.34
  - Port: 80
  - Info: GET /index.html HTTP/1.1

---

### Bonus: ICMP (Ping)
- **Purpose**: Sends error messages and test connectivity.
- **Example Packet**:
  - Timestamp: 14.271099
  - Source: 192.168.0.10
  - Destination: 8.8.8.8
  - Info: Echo (ping) request