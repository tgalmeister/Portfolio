# 👨‍💻 Tanner Galmeister

📍 American Fork, UT • 📧 tanner.galmeister@gmail.com • 🌐 [LinkedIn](https://www.linkedin.com/in/tanner-galmeister/)

Hi there! I'm Tanner, I have a strong background in system administration, security operations, automation, and log analytics. I enjoy building efficient pipelines, developing detection capabilities, and automating response workflows to defend against modern cyber threats.

---

## 🛡️ Core Skills

- **SIEM & Detection Engineering**: Rapid7 InsightIDR, Microsoft Defender EDR, CrowdStrike Falcon, SecurityOnion, Wazuh  
- **Log Management & Enrichment**: Cribl Stream & Edge, Elastic Stack  
- **Security Automation & Orchestration**: Torq.ai, CommandZero, Microsoft Graph API  
- **Threat Intelligence & Investigation**: Proofpoint, CrowdStrike Falcon, Microsoft Defender TI  
- **Cloud & Identity Security**: Azure AD / Entra ID, Okta (SAML SSO), Intune, Addigy, Jamf  
- **Offensive Security Tools**: Metasploit, Burp Suite, Nmap, Nessus, Wireshark, Cuckoo Sandbox  
- **Frameworks & Compliance**: MITRE ATT&CK, NIST CSF, PCI-DSS

---

## 🚀 Projects & Work Highlights

### 🔎 AI-Based Phishing URL Detection
Built a robust phishing URL detection pipeline combining static URL feature analysis with machine learning. Integrated multiple datasets, including labeled legacy and novel phishing sources. Extracted lexical and structural features (e.g., URL length, domain complexity, subdomain entropy), and engineered indicators for obfuscation techniques and HTTPS usage. Applied dataset balancing via `RandomOverSampler`, and tuned a `RandomForestClassifier` using `RandomizedSearchCV`.

Performed recursive feature elimination with cross-validation (RFECV) to reduce overfitting and improve generalization. Evaluated performance through stratified validation, 5-fold cross-validation, and out-of-distribution testing using an external phishing dataset to measure domain shift. Also implemented a live prediction loop for real-time phishing detection.

**Tools & Libraries:** Python, `scikit-learn`, `imbalanced-learn`, `pandas`, `swifter`, `joblib`, `tldextract`, `matplotlib`, `seaborn`  
**Techniques:** Feature engineering, resampling, hyperparameter tuning, RFECV, domain shift analysis, model serialization 
 
🔗 [View Project](https://github.com/tgalmeister/AI-Based-Phishing-URL-Detection)

---

### 🔁 AI-Driven SOC Automation (Torq.ai)
Designed and deployed AI-driven automation workflows using the Torq.ai platform to streamline SOC operations—automating case creation, enriching alerts with contextual intelligence, and executing dynamic runbooks for repetitive tasks such as phishing email triage and response.
**Tools**: Torq.ai, Microsoft Graph, Exchange, Virustotal  

---

### 🧰 SIEM & Log Pipeline with Cribl
Optimized Cribl Stream and Edge pipelines to enhance real-time log ingestion, enrichment, and routing for security and operational analytics. Deployed and configured Cribl Edge agents on endpoints and servers to collect telemetry data and forward it to Rapid7 InsightIDR, improving visibility and reducing noise through targeted filtering.
**Tech:** Cribl, JSON, REST API, Graph API  

---

### 📦 ModSecurity WAF Ruleset
This project demonstrates the installation, configuration, and testing of ModSecurity with the OWASP Core Rule Set (CRS) on an Ubuntu SEED virtual machine to protect against common web application attacks, including SQL Injection (SQLi), Cross-Site Scripting (XSS), and Cross-Site Request Forgery (CSRF). After installing and tuning ModSecurity, custom rules were developed and tested against known vulnerable websites, successfully blocking exploitation attempts and verifying protection through server audit logs. The project showcases how ModSecurity, even with default CRS settings, can effectively defend against many critical web security threats when properly configured.

**Tools**: ModSecurity, OWASP Core Rule Set (CRS), Ubuntu SEED VM, Apache2, SeedLab Test Sites (SQLi, XSS, CSRF)

🔗 [View Project](https://github.com/tgalmeister/modsecurity-rules)


---

### 🧪 Active Directory Attack Lab - Coming Soon
Building a home lab with Proxmox and simulated Windows AD infrastructure to test lateral movement, pass-the-hash, Golden Ticket attacks, and endpoint defenses.  
**Tools:** Mimikatz, BloodHound, CrackMapExec, Sysmon  

🔗 [View Project](https://github.com/tgalmeister/proxmox)

---

### ⚙️ Cross-Platform Automation & Scripting Toolkit

Developed a versatile collection of automation scripts spanning PowerShell, Python, and Bash to streamline daily administrative and security tasks across Windows and Linux environments. Key scripts include PowerShell modules for Exchange Online mailbox management, permission auditing, and mail flow troubleshooting; Python scripts for system monitoring, file processing, and API integrations; and Bash scripts for log rotation, system updates, and service orchestration on Linux servers. Emphasized modular design, error handling, and logging to ensure reliability and maintainability. Several scripts integrate with Microsoft Graph API and other cloud services to automate complex workflows and reporting.

**Tools & Languages:** PowerShell, Python, Bash, Microsoft Graph API, Exchange Online, Linux CLI

🔗 [View Project](https://github.com/tgalmeister/scripting)

---

## 🧠 Education & Certifications

🎓 **M.S. Cybersecurity**, Utah Valley University (2025)  

🎓 **B.S. Information Management**, Utah Valley University (2019)

📜 **Certifications**  
- CEH - In Progress
- CompTIA Security+ (2024)  
- ISC2 Certified in Cybersecurity (CC) (2024)

## 📚 Research & Publications

| Year | Paper | Course / Context | Highlights |
|------|-------|------------------|------------|
| 2025 | **[Phishing URL Detection Using Machine Learning](https://github.com/tgalmeister/AI-Based-Phishing-URL-Detection)** <br> | M.S. Cybersecurity — Capstone / Independent Research | • Trained Random Forest, XGBoost, and LSTM models on the PhiUSIIL dataset (235 k URLs).<br>• Engineered 25+ URL features, balanced classes with SMOTE, and achieved 98 % F1 on external test sets.<br>• Benchmarked model drift, produced ROC/PR curves, and released Jupyter notebooks & Dockerfile for reproducibility. |
| 2025 | **[Cyberlaw for Software Companies](https://github.com/tgalmeister/Law-Ethics-Privacy-in-Cybersecurity)** <br> | Law, Ethics, and Privacy in Cybersecurity | • Analyzes legal obligations and ethical considerations for SaaS vendors.<br>• Covers vulnerability disclosure, breach-notification, and global privacy laws (GDPR, CCPA).<br>• Recommends governance frameworks for secure-by-design development. |

> 📌 *Each paper is attached to a repository—feel free to download and read.*


## 🧪 Hands-On & Community

- 👾 Platforms: TryHackMe | HackTheBox | HackerOne CTF
- 🧰 Homelab: AD attack lab - in progress, Unifi Network, IDS/IPS, HomeAssistant, Media Server 


---

## 📬 Let’s Connect

I'm always open to collaboration, threat research, or talking about ways to improve security automation and detection engineering.  
📧 **Email:** tanner.galmeister@gmail.com  
🌐 **LinkedIn:** [linkedin.com/in/tanner-galmeister](https://linkedin.com/in/tanner-galmeister)

> ✨ *Thanks for visiting — feel free to fork this portfolio template!*
