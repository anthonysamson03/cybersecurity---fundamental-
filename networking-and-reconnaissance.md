# Task: Networking & Reconnaissance Fundamentals

This repository documents fundamental computer networking concepts and the practical application of basic command-line tools used to gather information during the reconnaissance phase of an ethical hacking assessment.

---

## 1. Core Networking Concepts

Before attempting to secure or analyze a system, it is vital to understand how data moves across a network.

### 🌐 IP Addresses (Internet Protocol)
An IP address is a unique identifier assigned to every device connected to a computer network.
* **IPv4:** A 32-bit address format expressed as four decimal numbers separated by dots (e.g., `192.168.1.1`).
* **IPv6:** A 128-bit address format written in hexadecimal to accommodate the growing number of global devices (e.g., `2001:db8::ff00:42:8329`).

### 🏷️ DNS (Domain Name System)
DNS acts as the "phonebook of the Internet." It translates human-readable domain names (like `google.com`) into machine-readable IP addresses (like `142.250.190.46`).

### 🚪 Ports and Protocols
* **Ports (0 to 65535):** Virtual channels used by devices to differentiate between types of network traffic. 
* **Protocols:** The structured rules governing how data is sent and received.

**Common Port/Protocol Examples:**
* **Port 80 (HTTP):** Unencrypted web traffic.
* **Port 443 (HTTPS):** Encrypted, secure web traffic.
* **Port 22 (SSH):** Secure remote command-line access.
* **Port 53 (DNS):** Domain Name System resolution.

---

## 2. Introduction to Reconnaissance

**Reconnaissance (Recon)** is the very first phase of an ethical hacking lifecycle. It involves gathering as much information as possible about a target system, organization, or network infrastructure.

* **Passive Recon:** Gathering data without interacting directly with the target (e.g., searching public registries, WHOIS data, or social media records). This leaves zero trace on the target's logs.
* **Active Recon:** Interacting directly with the target system to uncover vulnerabilities (e.g., port scanning or sending direct web queries). This can be logged by firewalls and Intrusion Detection Systems (IDS).

---

## 3. Practical DNS Reconnaissance via Command Line

Using standard terminal utilities like **`nslookup`** allows security professionals to queries DNS servers and extract crucial public domain records.

### Command 1: Basic Domain Resolution
To find the IP address associated with a public domain name:
```bash
nslookup google.com
