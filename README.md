#  Task 5 – Network Traffic Capture with Wireshark

## 📌 Objective
To capture and analyze live network traffic using **Wireshark**, identify key protocols, and practice filtering and analysis.

## 🛠 Tools Used
- **Wireshark**
- **Browser (Chrome/Firefox)**
- **Command Prompt (ping utility)**

## 📁 Files Included
task-5-wireshark/
├── capture.pcap # Exported packet capture file
├── report.md # Protocol summary and sample packets
└── screenshots/
├── png
└── png

## 🧪 Process
1. Installed Wireshark and selected active interface.
2. Captured live traffic while browsing websites and pinging external servers.
3. Applied protocol filters: `http`, `dns`, `tcp`, `icmp`
4. Exported `.pcap` file and recorded observations.

## 🔍 Example Filters Used
- DNS: `dns`
- HTTP: `http`
- TCP: `tcp.port == 80`
- ICMP: `icmp`

## 📸 Screenshots
- Filtered DNS/HTTP packets
