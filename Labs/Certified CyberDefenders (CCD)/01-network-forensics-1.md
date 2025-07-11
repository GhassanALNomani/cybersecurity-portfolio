
# 🧪 Lab 01: Network Forensics 1

**Platform:** [CyberDefenders]  
**Category:** Network Forensics  
**Status:** ✅ Completed  
**Date:** July 10, 2025  
**Tools Used:** Wireshark, Zui, PCAP, NetworkMiner, VirusTotal, DNS & HTTP investigation

---

## 🔍 Objective

Analyze a network trace captured across multiple systems to uncover attack details; determining the attack source, and data exfiltrationion.

---

## 🧰 Key Skills Practiced

- Filtering and navigating PCAP data using Wireshark
- Extracting artifacts from HTTP sessions (e.g., EXE, ZIP files)
- Reconstructing TCP streams for attacker behavior
- Identifying suspicious DNS queries and IPs
- Analyzing HTTP headers, user agents, and file downloads
- Detecting command-and-control (C2) communication patterns

---

## 🧠 Key Takeaways

- Strategic filtering (e.g. `http.request`, `dns`, `tcp.stream`) greatly reduced noise and accelerated analysis
- The PCAP revealed attacker actions such as payload downloads and remote C2 beaconing
- Indicators such as anomalous DNS behavior, unusual user-agents, or encoded payloads revealed hidden attacker infrastructure


---

## 🔗 Achievement Badge  
[CyberDefenders – Network Forensics 1 Lab](https://cyberdefenders.org/online-labs/achievements/GhassanALNumani/network-forensics-2/)

---

✅ This lab reinforces real-world network forensic skills critical to incident response, threat detection, and SOC investigations.


---

> 💬 Let’s connect and collaborate on forensics or SOC projects:  
> [LinkedIn – Ghassan AlNomani](https://www.linkedin.com/in/ghassan-alnomani/)
