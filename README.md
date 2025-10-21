# 🛡️ Cybersecurity Home Lab

This repository documents my personal **Cybersecurity Learning Lab**, built entirely on **Hyper-V (Windows 10)** for practical experience in **security operations, system administration, and automation**.

---

## 🧰 Lab Environment

| Component | Role | OS |
|------------|------|----|
| **DC01** | Domain Controller / DNS | Windows Server 2025 |
| **SRV2022** | Security & Monitoring Node | Windows Server 2022 |
| **SRV2016** | Application / Target Server | Windows Server 2016 |
| **UBUNTU24** | Vulnerability Scanner & Log Forwarder | Ubuntu Server 24 |

---

## 🧩 Key Projects

### 🔹 1. Active Directory & Domain Setup
- Configured AD DS, DNS, and domain joins  
- Managed users, groups, and GPOs  

### 🔹 2. Centralized Monitoring with Graylog
- Integrated **Winlogbeat** + **Sysmon**  
- Tracked PowerShell activity, policy changes, and failed logons  

### 🔹 3. Vulnerability Assessment
- Installed and configured **OpenVAS**  
- Scanned both Windows and Ubuntu systems  

### 🔹 4. Hardening & Baseline Enforcement
- Applied Microsoft Security Baselines  
- Hardened RDP, SMB, and SSH  
- Implemented least-privilege and firewall rules  

### 🔹 5. Incident Response Simulation
- Simulated brute-force + PowerShell attacks  
- Detected via Graylog, contained with PowerShell automation  
- Completed the full cycle: **Detection → Containment → Eradication → Recovery**

---

## ⚙️ Automation Scripts

| Script | Purpose |
|--------|----------|
| `powershell_auto_block.ps1` | Automatically blocks IPs after repeated failed logons |
| `log_audit.ps1` | Collects key security events |
| `scheduled_tasks_monitor.ps1` | Detects unauthorized persistence |

---

## 🧾 Reports & Deliverables

| File | Description |
|------|--------------|
| `ir_report_2025.docx` | Incident Response documentation |
| `openvas_scan_results.pdf` | Vulnerability assessment output |
| `gpo_baseline_report.md` | Hardening baseline summary |

---

## 🚀 Future Enhancements
- Integrate **Wazuh / Elastic SIEM**
- Add **Defender for Identity**
- Expand PowerShell automation with **Python & APIs**

---

### 👤 Author

**Crispus Omollo**  
💼 Cybersecurity Technician | System Administrator | IT Innovator  
🔗 [LinkedIn Profile](https://linkedin.com/in/crispusomollo)  
📧 crispusomollo@gmail.com


