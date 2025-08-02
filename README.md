# Phase 5: Application and Data Security  
**Cybersecurity Internship – Phase 5 Deliverables and Documentation**

## 📌 Overview

This phase of the internship focused on securing applications and sensitive data through a combination of automated scanning tools, encryption techniques, and implementation of data loss prevention (DLP) measures. The target application for testing was **OpenCart** running on a secured Ubuntu virtual machine. All configurations, testing, and screenshots were performed and documented within a controlled lab environment.

---

## 🧩 Key Activities

### 1. 🔎 OWASP ZAP Web Application Vulnerability Assessment
- Installed and launched OWASP ZAP.
- Performed **Active Scanning** on the OpenCart instance.
- Discovered and analyzed vulnerabilities including potential **XSS**, **missing headers**, and **input validation issues**.
- Exported a complete vulnerability report in HTML format.

📁 Output:  
- `zap_report.html` – Full vulnerability scan report.

---

### 2. 🔐 Data Encryption using OpenSSL
- Used `openssl enc` to **encrypt OpenCart's `config.php` file** with AES-256-CBC.
- Demonstrated manual decryption using the correct password to validate data confidentiality.

📁 Outputs:  
- `config.php.enc` – Encrypted config file.  
- `config_decrypted.php` – Successfully decrypted file for integrity verification.

---

### 3. 🛡️ Data Loss Prevention (DLP) Measures
- Discussed and simulated real-world DLP techniques to protect sensitive data:
  - **File permission hardening** on sensitive files like `config.php`.
  - **Local monitoring** of copied, shared, or exfiltrated files using manual audit trails and screenshot proof.
  - **Securing shared folders** between the host and guest OS (VirtualBox Shared Folder: `sf_Pictures`).

📸 Screenshot evidence included for:
- Encryption & decryption processes.
- OWASP ZAP scan interface.
- File access controls and permissions on critical data.

---

### 4. 🧰 Tools and Environment Used

| Tool/OS           | Purpose                                      |
|-------------------|----------------------------------------------|
| Ubuntu Linux VM   | Hosting OpenCart web application             |
| OWASP ZAP         | Web application vulnerability scanning       |
| OpenSSL           | File encryption/decryption                   |
| VirtualBox Shared Folder (`sf_Pictures`) | Screenshot and evidence capture |
| GitHub            | Documentation and public showcase repository |

---

## 📂 Repository Contents

| File Name                  | Description                                          |
|---------------------------|------------------------------------------------------|
| `zap_report.html`         | Full OWASP ZAP report on OpenCart                   |
| `config.php.enc`          | Encrypted OpenCart configuration file               |
| `config_decrypted.php`    | Decrypted copy for validation purposes              |
| `README.md`               | Detailed project summary (this file)                |
| `phase5_screenshots/`     | All evidence screenshots from encryption, scans, etc |

---

## 🧠 Skills Demonstrated

- Vulnerability assessment with industry-grade tools.
- Practical knowledge of cryptographic data protection.
- Manual DLP simulations and implementation understanding.
- Secure documentation and professional reporting standards.

---

## ✅ Final Notes

This work is part of a larger cybersecurity internship that simulates real-world scenarios. All tests and tools were used in a virtualized lab environment and follow ethical security practices. This phase builds a solid foundation in **application security**, **data protection**, and **secure configuration management**.

---

**Prepared and Executed by:**  
`Rulane Hlongwani` (Cybersecurity Intern)  
GitHub:  (https://github.com/rlinemavuyangwa)

📅 **Completed:** August 2, 2025  
🔐 **Internship Phase:** 5 

