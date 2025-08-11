# wireshark-task5-protocol-analysis
Packet capture and protocol analysis using Wireshark. Includes .pcapng capture, screenshots of HTTP, DNS, TCP, UDP, ICMP, and QUIC traffic, and a summary report. Demonstrates filtering, protocol identification, and practical network analysis skills.
# Wireshark Task 5 – Protocol Analysis

## 📌 Overview
This project is part of my Cyber Security Internship (Task 5), where the objective was to:
- Capture live network packets.
- Identify different network protocols.
- Apply protocol filters in Wireshark.
- Export the packet capture file.
- Summarize findings in a structured report.

## 🛠 Tools Used
- **Wireshark** (Packet Capture and Analysis)

wireshark-task5-protocol-analysis/
│
├── 📄 task5_capture.pcapng # The main packet capture file
│
├── 📂 screenshots/ # Screenshots showing protocol filtering & analysis
│ ├── Screenshot_2025-08-11_110345.png # Protocol hierarchy statistics
│ ├── Screenshot_2025-08-11_110557.png # TCP protocol packets
│ ├── Screenshot_2025-08-11_110624.png # UDP protocol packets
│ ├── Screenshot_2025-08-11_110705.png # DNS protocol packets
│ ├── Screenshot_2025-08-11_110746.png # HTTP protocol packets
│ ├── Screenshot_2025-08-11_110825.png # ICMP protocol packets
│ ├── Screenshot_2025-08-11_110902.png # QUIC protocol packets
│
└── 📄 README.md # Project documentation (this file)

---

## 📊 Protocols Identified & Summary

1. **TCP (Transmission Control Protocol)**  
   - Connection-oriented protocol.
   - Used by HTTPS, HTTP, and TLS traffic.
   - Example: Packet exchanges between browser and websites.

2. **UDP (User Datagram Protocol)**  
   - Connectionless protocol, faster but less reliable.
   - Used by QUIC and DNS traffic.

3. **DNS (Domain Name System)**  
   - Resolves domain names to IP addresses.
   - Example: Queries to `google.com`, `amazontrust.com`.

4. **HTTP (Hypertext Transfer Protocol)**  
   - Protocol for transferring web content.
   - Example: GET and POST requests.

5. **ICMP (Internet Control Message Protocol)**  
   - Used for diagnostics and network reachability.
   - Example: Ping requests and replies to 8.8.8.8.

6. **QUIC (Quick UDP Internet Connections)**  
   - Encrypted, UDP-based protocol used by modern web apps.
   - Example: Google and YouTube connections.

---

## 🔍 How to Open & View the Capture
1. Install **Wireshark** from [https://www.wireshark.org/download.html](https://www.wireshark.org/download.html)
2. Open `task5_capture.pcapng` in Wireshark.
3. Use filters like:
   - `tcp`
   - `udp`
   - `dns`
   - `http`
   - `icmp`
   - `quic`
4. Analyze packet details in the middle and lower pane.

---

## 📚 Key Learning Outcomes
- Understanding packet structure and protocol headers.
- Using Wireshark filters for focused analysis.
- Identifying and interpreting network protocols.
- Exporting capture data for reporting.

---

## 📜 References
- [Wireshark User Guide](https://www.wireshark.org/docs/)
- [TCP/IP Model Overview](https://en.wikipedia.org/wiki/Internet_protocol_suite)

---

**Author:** Naman Patil  
**Date:** 11 August 2025
