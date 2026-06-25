# Task: Penetration Testing Simulation

This repository documents the execution of a complete, controlled penetration testing lifecycle inside a dedicated host-isolated sandbox lab environment. The objective is to identify, analyze, and exploit architectural flaws to understand system defenses.

---

## 1. Phase 1: Environment Setup & Target Discovery

Before testing can begin, the attacker machine (Kali Linux) and the target system must be configured on the same isolated virtual host network.

### 🌐 Network Host Discovery
To discover the exact local IP address of the vulnerable target machine on the network, an initial subnet scan is performed:
```bash
sudo nmap -sn 192.168.1.0/24
