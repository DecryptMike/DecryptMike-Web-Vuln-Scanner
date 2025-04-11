<p align="center">
  <img src="DecryptMikeLogo.png" alt="DecryptMike Logo" style="max-width: 100%; height: auto;"/>
</p>

<h2 align="center">
   🔍 Web Vulnerability Scanner 
</h2>

A lightweight Python-based tool to scan websites for common vulnerabilities.  
Built in Python with a focus on practical cybersecurity automation.

---

## ✅ Features

- 🔓 Detects common admin panels  
- 👾 Tests for reflected XSS  
- 💉 Scans for SQL Injection error messages  
- 🪟 Checks for missing clickjacking protection  
- 📂 Detects open directory listings  
- 🧬 Scans server headers for outdated technologies  

---

## 📦 Requirements

- Python 3.6+
- `requests`
- `beautifulsoup4`

To install dependencies, run:

```bash
pip install -r requirements.txt
```
--- 

## 🚀 Usage

### 1. Clone the repo (or download ZIP)
```bash
git clone https://github.com/DecryptMike/DecryptMike-Web-Vuln-Scanner.git
cd DecryptMike-Web-Vuln-Scanner 
```
### 2. Create and activate a virtual enviroment 
```bash
python3 -m venv venv
source venv/bin/activate
```
### 3. Install dependencies 
```bash
pip install -r requirements.txt
```
### 4. Run the scanner
```bash
python scanner.py
```
### 5. Enter the target URL when prompted
```bash
http://testphp.vulnweb.com
```
---

## 🧠 Sample Output 

[+] Scanning http://testphp.vulnweb.com for vulnerabilities...
[*] Checking for common admin pages...
[!] Potential admin page found: http://testphp.vulnweb.com/admin
[*] Checking for reflected XSS...
[+] No reflected XSS found.
[*] Checking for SQL Injection...
[+] No obvious SQL Injection vulnerability found.
[*] Checking for Clickjacking protection...
[!] No Clickjacking protection found
[*] Checking for directory listing...
[!] Directory listing found: http://testphp.vulnweb.com/images/
[*] Checking server headers...
[+] Server Header: nginx/1.19.0
[+] X-Powered-By Header: PHP/5.6.40
[!] Potential outdated technology detected

---

## ⚠️ Legal Disclaimer
This tool is intended for educational and authorized testing only.
Do not use it to scan websites without proper permission.

---

## 💻 Built by @DecryptMike

---

### ✅ Once You Paste:

1. Save the file as `README.md` (not `.txt`, not `.py`)
2. Open the **Markdown Preview** in VS Code:
   - Press `Cmd + Shift + V` (on Mac) or `Ctrl + Shift + V` (on Windows)
   - Or right-click inside the file → **"Open Preview"**

You’ll see the properly rendered GitHub-style formatting ✅

---

### Last Step:

Push it to GitHub:
```bash
git add README.md
git commit -m "Final full README with markdown formatting"
git push origin main
```
