# 🖥️ Home Network Port Scan

## 🎯 Objective
Perform a port scan on my local machine to identify open ports and running services.

---

## 🛠️ Tools Used
- Nmap

---

## 📡 Target Information
- Target Domain: scanme.nmap.org
- Scan Type: TCP Connect Scan

---

## 🔎 Scan Command

```bash
nmap -Pn -sC -sV -oN scan.txt scanme.nmap.org

'''
-Pn → skip host discovery (host may block ping)
-sC → run default scripts
-sV → detect service versions
-oN → save output to file 
'''