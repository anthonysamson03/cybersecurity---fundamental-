# Cybersecurity Fundamentals & Ethical Hacking
This documentation covers the foundational principles of cybersecurity, ethical hacking, threat models, and core industry frameworks based on the core curriculum of cybersecurity fundamentals.
---
## 1. Core Principles of Cybersecurity & Ethical Hacking
**Cybersecurity** is the practice of protecting systems, networks, programs, and data from digital attacks, damage, or unauthorized access. 
**Ethical Hacking** (also known as penetration testing or white-hat hacking) involves legally and deliberately probing networks and systems to find security vulnerabilities that a malicious hacker could exploit. 
### Key Differences

| Feature | Cyber Defense (Blue Team) | Ethical Hacking (Red Team) |
| :--- | :--- | :--- |
| **Objective** | Protect and defend assets. | Find and exploit vulnerabilities to test defenses. |
| **Approach** | Reactive & Proactive (Firewalls, Monitoring). | Offensive (Simulating real-world attacks). |

---
## 2. Types of Hackers
Hackers are generally categorized by their intent and whether they have authorization:
* **White Hat Hackers (Ethical Hackers):** Secure systems with explicit permission. They find flaws to fix them.
* **Black Hat Hackers (Cracker/Malicious):** Violate computer security for personal gain, malicious intent, or cyber espionage without authorization.
* **Grey Hat Hackers:** Fall between white and black hats. They may exploit a vulnerability without permission but do so to bring it to the owner's attention rather than cause harm.
---
## 3. The CIA Triad
The **CIA Triad** is the foundational model designed to guide information security policies within an organization.
### 🔴 Confidentiality
Ensures that sensitive information is accessible **only** to authorized users. 
* *How it's enforced:* Encryption (AES, RSA), Access Control Lists (ACLs), Multi-Factor Authentication (MFA).
### 🔴 Integrity
Ensures that data remains accurate, consistent, and unaltered during storage or transmission except by authorized modifications.
* *How it's enforced:* Hashing (SHA-256), Digital Signatures, Version Control.
### 🔴 Availability
Ensures that systems, networks, and data are fully accessible to authorized users whenever they are needed.
* *How it's enforced:* Hardware Redundancy, Regular Backups, DDoS Mitigation Services.
---
## 4. Common Threats and System Impact
### 🛠️ Malware (Malicious Software)
* **Definition:** An umbrella term for tracking software designed to disrupt, damage, or gain unauthorized access to a computer system (e.g., viruses, worms, Trojans).
* **System Impact:** Slows down system performance, steals data in the background, leaks user credentials, and can completely corrupt OS files.
### 🎣 Phishing
* **Definition:** A social engineering attack where bad actors masquerade as trusted entities via email, text, or malicious links to trick users into revealing sensitive data.
* **System Impact:** Leads to credential theft, unauthorized access to corporate networks, and serves as an entry vector for malware delivery.
### 🔐 Ransomware
* **Definition:** A specific type of malware that encrypts a victim's files. The attacker then demands a ransom payment (typically in cryptocurrency) to provide the decryption key.
* **System Impact:** Completely locks business-critical data, disrupts operations, causes severe financial losses, and can result in permanent data destruction if backups aren't available.