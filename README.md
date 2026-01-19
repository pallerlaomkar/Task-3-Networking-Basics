
# Task 3: Networking Basics for Cyber Security

## 📌 Objective
The objective of this task is to understand fundamental networking concepts and analyze real-time network traffic using packet analysis tools. This task focuses on identifying network protocols, observing TCP connections, analyzing DNS queries, and understanding the difference between encrypted and unencrypted traffic.

---

## 🛠️ Tools Used
- **Primary Tool:** Wireshark  
- **Alternative Tools:** tcpdump, Microsoft Network Monitor  

---

## 📚 Networking Concepts Covered
- IP Address  
- MAC Address  
- DNS (Domain Name System)  
- TCP and UDP  
- Packet Sniffing  
- HTTP vs HTTPS  

---

## 🔍 Methodology
1. Installed Wireshark and selected the active network interface.
2. Captured live network traffic while browsing websites.
3. Applied protocol-based filters such as TCP, DNS, HTTP, and HTTPS.
4. Observed the TCP three-way handshake process.
5. Identified plain-text (HTTP) and encrypted (HTTPS) traffic.
6. Captured and analyzed DNS queries.
7. Saved the packet capture file for analysis.
8. Documented observations in a structured analysis report.

---

## 📊 Observations
- TCP connections follow a three-way handshake (SYN, SYN-ACK, ACK).
- DNS resolves domain names into IP addresses.
- HTTP traffic is transmitted in plain text and is insecure.
- HTTPS traffic is encrypted using TLS, ensuring secure communication.
- Packet sniffing can expose sensitive information if encryption is not used.

---

## 📁 Repository Structure
```
Task-3-Networking-Basics/
│
├── network_analysis_task3.pcapng
├── Task_3_Networking_Basics_Analysis_Report.pdf
├── README.md
```

---

## ✅ Final Outcome
- Gained hands-on experience with network traffic analysis.
- Developed the ability to analyze TCP, DNS, HTTP, and HTTPS traffic.
- Understood the importance of encrypted communication.
- Built a strong foundation for cybersecurity and SOC-related roles.

---

## 📌 Notes
- This task was completed using free and open-source tools.
- Self-research and debugging were performed to enhance learning.
