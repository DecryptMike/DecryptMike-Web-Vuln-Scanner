![Python](https://img.shields.io/badge/Python-3.6%2B-blue?logo=python)
![Last Commit](https://img.shields.io/github/last-commit/DecryptMike/DecryptMike-Web-Vuln-Scanner)
![License](https://img.shields.io/github/license/DecryptMike/DecryptMike-Web-Vuln-Scanner)
![Made With](https://img.shields.io/badge/Made%20with-Shields.io-007ec6?logo=shieldsdotio)

<p align="center">
  <img src="DecryptMikeLogo.png" alt="DecryptMike Logo" style="max-width: 100%; height: auto;"/>
</p>

<h2 align="center">
   🔍 Web Vulnerability Scanner 
</h2>

<h4 align="center">
  The Decrypt Mike Web Vunerability Scanner Is A Lightweight Python-Based Tool To Scan Websites For Common Vulnerabilities.<br>Built In Python With A Focus On Practical Cybersecurity Automation.
</h4>

## 📄 License

* This repository is licensed under the (**Default Copyright Law**) which prohibits the redistribution or reuse of its content. <br>
* However, others are welcome to explore, gain insights, and utilize the materials solely for **personal** learning and reference purposes.

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

To Install Dependencies, Run:

```bash
pip install -r requirements.txt
```
--- 

## 🚀 Usage

### 1. Clone The Repo (Or Download ZIP)
```bash
git clone https://github.com/DecryptMike/DecryptMike-Web-Vuln-Scanner.git
cd DecryptMike-Web-Vuln-Scanner 
```
### 2. Create And Activate A Virtual Enviroment 
```bash
python3 -m venv venv
source venv/bin/activate
```
### 3. Install Dependencies 
```bash
pip install -r requirements.txt
```
### 4. Run The Scanner
```bash
python scanner.py
```
### 5. Enter The Target URL When Prompted
```bash
http://testphp.vulnweb.com
```
---

## 🧠 Sample Output 

```
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
```

---

## ⚠️ Legal Disclaimer
This Tool Is Intended For Educational And Authorized Testing Only.
Do Not Use It To Scan Websites Without Proper Permission.

---

## 💻 Built By @DecryptMike

---

### ✅ Once You Paste:

1. Save the file as `README.md` (not `.txt`, not `.py`)
2. Open the **Markdown Preview** in VS Code:
   - Press `Cmd + Shift + V` (on Mac) or `Ctrl + Shift + V` (on Windows)
   - Or right-click inside the file → **"Open Preview"**

You’ll See The Properly Rendered GitHub-Style Formatting ✅

---

### Last Step:

Push It To GitHub:
```bash
git add README.md
git commit -m "Final full README with markdown formatting"
git push origin main
```
