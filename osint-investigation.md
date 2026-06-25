# Task: Open Source Intelligence (OSINT) Investigation

This repository documents the foundational methodologies, tools, and frameworks used to conduct an Open Source Intelligence (OSINT) investigation. The objective is to map a target's digital footprint using legal, publicly available information resources.

---

## 1. What is OSINT?

**Open Source Intelligence (OSINT)** is the practice of collecting, analyzing, and making decisions based on data accessible to the general public. It is utilized by ethical hackers, digital investigators, and security teams during the passive reconnaissance phase to understand exactly what information an adversary can find online.

### ⚖️ The Golden Rule of OSINT
> **"Look, but don't touch."** 
> OSINT is strictly passive. You are gathering data that is already out there (social media, public registries, leaked databases). You are *not* interacting with or exploiting the target's direct infrastructure.

---

## 2. The OSINT Cycle (Investigation Workflow)

A professional cyber investigation follows a systematic loop rather than random searching:

1. **Direction/Requirements:** Defining what you need to find (e.g., locating a person, finding a company's exposed servers).
2. **Data Collection:** Gathering raw data using automated tools and manual searches.
3. **Processing & Organization:** Filtering out the noise, verifying sources, and structuring the data.
4. **Analysis & Production:** Connecting the dots to build a cohesive picture or narrative.
5. **Dissemination:** Presenting the actionable intelligence to stakeholders or in a formal report.

---

## 3. Core OSINT Pillars & Tools

Real-world investigations usually focus on specific categories of public data footprints:

### 👤 1. People Intelligence (Sock Puppets & Social Media)
* **Concept:** Investigating individuals through their social media accounts, forum posts, and public registries.
* **Best Practice:** Investigators use **Sock Puppets**—entirely fake, disconnected online personas with clean digital histories—to view target profiles safely without alerting the target or exposing their personal identity.
* **Common Tools:** `WhatsMyName.app` (to find usernames across hundreds of websites), reverse image search engines (Google Lens, Yandex, PimEyes).

### 🌐 2. Domain & Infrastructure Intelligence
* **Concept:** Mapping out an organization's public-facing digital assets, subdomains, and historical server setups.
* **Key Tools:**
  * **WHOIS Lookups:** Identifies domain registration details, ownership dates, and contact emails.
  * **DNSDumpster:** A research tool that maps out an organization's entire DNS structure visually.
  * **Shodan:** A search engine for internet-connected devices, allowing investigators to find exposed routers, webcams, or databases.

### 📧 3. Email & Breach Intelligence
* **Concept:** Finding valid company email addresses and cross-referencing them against public database leaks to check for compromised credentials.
* **Key Tools:**
  * **Hunter.io:** Scrapes the web to find public email syntax and specific addresses linked to a corporate domain.
  * **Have I Been Pwned (HIBP):** Checks if an email address has been compromised in known historical data breaches.

---

## 4. Investigative Frameworks: The OSINT Framework

To keep track of the thousands of specialized tools available, investigators rely on the **OSINT Framework** (`osintframework.com`). It acts as a comprehensive, interactive directory broken down by categories (e.g., IP addresses, digital currency, metadata, geolocating images) to guide an analyst to the right tool for their specific query.

---

## 5. Defensive Takeaways (OPSEC for Individuals)
* **Minimize Footprints:** Periodically Google yourself or your organization to see what public records are exposed.
* **Enforce MFA:** Since OSINT easily uncovers old corporate passwords via breach leaks, multi-factor authentication acts as a vital fail-safe.
* **Review Privacy Settings:** Restrict social media accounts to prevent bad actors from mapping out employee networks for targeted social engineering.

---

*Notes compiled as part of a foundational cybersecurity learning path.*
