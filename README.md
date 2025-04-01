# 🌐 Web-Attack-Analysis-Investigation  
This repository contains case studies and detailed investigations of web-based attacks such as SQL Injection, Cross-Site Scripting (XSS), and other web security threats.  


## 📖 About This Repository 
This project includes:
-🌐 **Web Application Attacks** (SQL Injection, XSS, CSRF, SSRF)
-🕵️ **Log Analysis & Threat Hunting** (Apache, Nginx, SIEM logs)
-🔥 **Exploits & Zero-Day Analysis** (Log4Shell, Spring4Shell)
-🚨 **Incident Response & Mitigation Strategies**

Each case includes: 
✅ **Event Logs & HTTP Headers**
✅ **Attack Analysis & Detection Techniques**
✅ **Indicators of Compromise (IoCs)**
✅ **Mitigation & Prevention Steps**

---

## 📂 Case Studies  
### 📌 Case 1: Phishing Email with Malicious Attachment  
- **Event ID:** `120`
- **Rule Triggered:** `SOC170 - Passwd Found in Requested URL - Possible LFI Attack`
- **Event Time:** `March 01, 2022, 10:10 AM`
- **Affected Host:** 'WebServer1006'
- **Source IP:** '106.55.45.162'
- **Destination IP:** '172.16.17.13'
- **HTTP Method:** 'GET'
- **Alert Trigger Reason:** "URL Contains passwd"
  

📄 **[Read Full Report](https://acrobat.adobe.com/id/urn:aaid:sc:ap:c8fee2d5-5774-4f95-b8d3-c62da9160420)** 

### 📌 Case 2: Phishing Email with Malicious Attachment  
- **Event ID:** '119'
- **Rule Triggered:** 'SOC169 - Possible IDOR Attack Detected'
- **Event Time:** 'Feb 28, 2022, 10:48 PM'
- **Affected Host:** 'WebServer1005'
- **Source IP:** '134.209.118.137'
- **Destination IP:** '172.16.17.15'
- **HTTP Method:** 'POST'
- **Requested URL:** "https://172.16.17.15/get_user_info/"
  

📄 **[Read Full Report]()** 


### 📌 Case 3:SQL Injection Attempt Detected
- **Event ID:** '166'
- **Rule Triggered:** 'SOC166 - SQL Injection Attempt Detected'
- **Event Time:** 'March 02, 2022, 02:35 AM'
- **Affected Host:** 'DatabaseServer01'
- **Source IP:** '185.220.101.45'
- **Destination IP:** '172.16.17.20'
- **HTTP Method:** 'GET'
- **Requested URL:** 'https://172.16.17.20/login?user=admin' OR 1=1--&'


📄 **[Read Full Report]()** 


### 📌 Case 4:XSS Attack Attempt Detected
- **Event ID:** '165'
- **Rule Triggered:** 'SOC165 - Cross-Site Scripting (XSS) Attempt'
- **Event Time:** 'March 05, 2022, 08:45 PM'
- **Affected Host:** 'CustomerPortal01'
- **Source IP:** '192.241.213.52'
- **Destination IP:** '172.16.18.30'
- **HTTP Method:** 'GET'
- **Requested URL:** 'https://172.16.18.30/comments?input=<script>alert('XSS')</script>'


📄 **[Read Full Report]()** 


### 📌 Case 5:Remote Code Execution (RCE) Attempt
- **Event ID:** '168'
- **Rule Triggered:** 'SOC168 - Remote Code Execution Attempt'
- **Event Time:** 'March 07, 2022, 06:20 PM'
- **Affected Host:** 'ApplicationServer03'
- **Source IP:** '45.76.23.110'
- **Destination IP:** '172.16.19.50'
- **HTTP Method:** 'POST'
- **Requested URL:** 'https://172.16.19.50/upload.php'


📄 **[Read Full Report]()**


### 📌 Case 6:Directory Traversal Attack Attempt
- **Event ID:** '167'
- **Rule Triggered:** 'SOC167 - Directory Traversal Attack'
- **Event Time:** 'March 09, 2022, 01:15 AM'
- **Affected Host:** 'FileServer05'
- **Source IP:** '103.120.112.21'
- **Destination IP:** '172.16.21.40'
- **HTTP Method:** 'GET'
- **Requested URL:** 'https://172.16.21.40/download?file=../../../../etc/shadow'


📄 **[Read Full Report]()**


---

## 🏆 About Me  
Cybersecurity Analyst passionate about **threat detection, incident response, and digital forensics**.  
🔗 **[LinkedIn Profile](WWW: https://www.linkedin.com/in/pawan pawar 72786b205/ )**  

---

## 🛡️ Tools Used  
🔹 **VirusTotal** – URL & File Reputation  
🔹 **Wireshark** – Network Packet Analysis  
🔹 **Hybrid Analysis** – Malware Sandboxing  
🔹 **Splunk/Kibana** – Log Analysis  

---

📌 **Want to connect?** Reach me on **[LinkedIn](WWW: https://www.linkedin.com/in/pawan pawar 72786b205/ )**.  

---

## 📌 Back to Main Page  
[🔙 Home](../README.md) 






