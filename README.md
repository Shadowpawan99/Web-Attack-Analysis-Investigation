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
  

📄 **[Read Full Report](https://drive.google.com/file/d/14GQSz7uaz8-Kr3Rk1f_9op9o7H4b7oFe/view?usp=drivesdk)** 


### 📌 Case 3:SQL Injection Attempt Detected
- **Event ID:** '166'
- **Rule Triggered:** 'SOC166 - SQL Injection Attempt Detected'
- **Event Time:** 'Feb 26, 2022, 06:56 PM'
- **Affected Host:** 'WebServer1002'
- **Source IP:** '112.85.42.13'
- **Destination IP:** '172.16.17.17'
- **HTTP Method:** 'GET'
- **Requested URL:** 'https://172.16.17.17/search/?q=<$script>javascript:$alert(1)<$/script>'


📄 **[Read Full Report](https://drive.google.com/file/d/14K1_tgGGlQyKdrik_06G47EQOE5QwdOW/view?usp=drivesdk)** 


### 📌 Case 4:Possible SQL Injection Payload Detected
- **Event ID:** '115'
- **Rule Triggered:** 'SOC165 - Possible SQL Injection Payload Detected'
- **Event Time:** 'Feb 25, 2022, 11:34 AM'
- **Affected Host:** 'Webserver1001'
- **Source IP:** '167.99.169.17'
- **Destination IP:** '172.16.169.17'
- **HTTP Method:** 'GET'
- **Requested URL:** 'https://172.16.17.18./search/?q=%22%20OR%201%20%3D%201%20%--%20-'


📄 **[Read Full Report](https://drive.google.com/file/d/14MOzAXeJMxZ8JxdsOUzlwbOxtqeoal15/view?usp=drivesdk)** 


### 📌 Case 5:Whoami Command Detected in Request Body
- **Event ID:** '118'
- **Rule Triggered:** 'SOC168 - Whoami Command Detected in Request Body'
- **Event Time:** 'Feb 28, 2022, 04:12 AM'
- **Affected Host:** 'Webserver1004'
- **Source IP:** '61.177.172.87'
- **Destination IP:** '172.16.17.16'
- **HTTP Method:** 'POST'
- **Requested URL:** 'https://172.16.17.16/video/'


📄 **[Read Full Report](https://drive.google.com/file/d/14LA5Z-fMj75L6uNXWWwSzC0exOlwh_qa/view?usp=drivesdk)**


### 📌 Case 6:LS Command Detected in Requested URL investigation
- **Event ID:** '117'
- **Rule Triggered:** 'SOC167 - LS Command Detected in Requested URL investigation '
- **Event Time:** 'Feb 27, 2022, 12:36 AM'
- **Affected Host:** 'EliotPRD'
- **Source IP:** '172.16.17.46'
- **Destination IP:** '188.114.96.15'
- **HTTP Method:** 'GET'
- **Requested URL:** 'https://letsdefend.io/blog/?=skills'


📄 **[Read Full Report](https://drive.google.com/file/d/14FoTaZS0kk6N7DjwBdBLMo1ZF651HQPh/view?usp=drivesdk)**


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
🔹 **AbuseIPDB** - IP reputation 

---

📌 **Want to connect?** Reach me on **[LinkedIn](WWW: https://www.linkedin.com/in/pawan pawar 72786b205/ )**.  

---

## 📌 Back to Main Page  
[🔙 Home](../README.md) 






