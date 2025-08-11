# Elevate Labs Task 5: Wireshark Network Traffic Analysis

This repository documents **Task 5** of my cybersecurity internship at **Elevate Labs**, where I captured and analyzed network traffic using Wireshark on Kali Linux. The goal was to identify and study multiple protocols, including HTTP, DNS, and TLS, by applying targeted filters and reviewing packet structures.

---

##  Task Objective

To use Wireshark for capturing and analyzing live network packets, apply protocol filters, and understand the purpose and structure of the captured traffic in a controlled environment.

---

##  System Details

- **OS**: Kali Linux 2024.2  
- **Tool**: Wireshark v4.x  
- **Network Interface**: `wlan0` (wireless) or `eth0` (wired)  
- **Target IP**: `192.168.150.133`

---

## Steps Performed

1. Launched Wireshark on Kali Linux with root privileges.  
2. Selected the active network interface.  
3. Started packet capture.  
4. Generated traffic by browsing a secure website (`openai.com`) and performing DNS lookups.  
5. Applied protocol filters for HTTP, DNS, and TLS.  
6. Stopped the capture and saved the `.pcap` file.  
7. Documented findings in a structured report.

---

## Protocols Identified

| Protocol | Purpose | Example from Capture |
|----------|---------|----------------------|
| **HTTP** | Transfers web page data between client and server. | GET request to openai.com |
| **DNS**  | Resolves domain names to IP addresses. | Query for `openai.com` |
| **TLS**  | Encrypts web traffic for confidentiality and integrity. | Encrypted HTTPS session to openai.com |

---

## Screenshots

Available in the `/screenshots` folder:
- `01-capture-overview.png`
- `02-http-filter.png`
- `03-dns-filter.png`
- `04-tls-filter.png`
- `05-packet-details.png`

---

## Files Included

- `Task5_Report.pdf` — Final internship report   
- `/screenshots` — Visual documentation of protocol analysis  
- `README.md` — This file

---

## ⚠️ Disclaimer

This project was completed as part of a cybersecurity internship at Elevate Labs and is intended **solely for educational and training purposes**. All traffic captures were performed on local or authorized networks. No unauthorized monitoring of third-party systems was conducted.

---
