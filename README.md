![Python](https://img.shields.io/badge/Python-3.6%2B-3776AB?style=flat&logo=python&logoColor=white&labelColor=3f3f46)
![Made with](https://img.shields.io/badge/Made%20with-Shields.io-0ea5e9?style=flat&logo=shieldsdotio&logoColor=white&labelColor=3f3f46)
![OWASP](https://img.shields.io/badge/OWASP-Top%2010-a21caf?style=flat&labelColor=3f3f46)
![Scanner](https://img.shields.io/badge/Scanner-Scanner-52525b?style=flat&labelColor=3f3f46)
![HTTP](https://img.shields.io/badge/HTTP-Protocol-38bdf8?style=flat&logo=protocols&labelColor=3f3f46)
![License](https://img.shields.io/github/license/DecryptMike/DecryptMike-Web-Vuln-Scanner)

<p align="center">
  <img src="DecryptMikeLogo.png" alt="DecryptMike Logo" style="max-width: 100%; height: auto;"/>
</p>

<h2 align="center">
   🔍 Web Vulnerability Scanner 
</h2>

<h4 align="center">
  The Decrypt Mike Web Vulnerability Scanner is a lightweight Python-based tool to scan websites for common vulnerabilities.<br>
  Built in Python with a focus on practical cybersecurity automation.
</h4>

---

## 🛠️ Features

- Detects exposed admin login portals  
- Tests for reflected XSS vulnerabilities  
- Scans for SQL injection error messages  
- Identifies missing clickjacking protection  
- Flags open directory listings (e.g., `/images/`)  
- Analyzes HTTP headers for outdated server technologies  
- **Exports scan results to both `.txt` and `.json` files**

---

## 📁 Tech Stack & Requirements

This project is built using:

- **Python 3.6+**
- `requests`, `beautifulsoup4`
- Command-line interface
- File export to `.txt` and `.json` formats

---

## 📸 Screenshot

<p align="center">
  <img src="DecryptMike Web Vuln Scanner.png" width="100%" alt="Sign In Page">
</p>

---

## 📦 To Install & Run:

Install all required dependencies using:

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
### 2. Create And Activate A Virtual Environment 
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

## ✅ Once You Paste

1. Save the file as `README.md` (not `.txt`, not `.py`)
2. Open the **Markdown Preview** in VS Code:
   - Press `Cmd + Shift + V` (on Mac) or `Ctrl + Shift + V` (on Windows)
   - Or right-click inside the file → **"Open Preview"**

You’ll See The Properly Rendered GitHub-Style Formatting ✅

---

## Last Step

Push It To GitHub:
```bash
git add README.md
git commit -m "Final full README with markdown formatting"
git push origin main
```
---

## 📄 Why I Built It

To sharpen my cybersecurity foundations and showcase how Python can automate critical vulnerability checks.  
This project was built for educational purposes and serves as a customizable base for more advanced tools.

---

## ⚠️ Legal Disclaimer
This Tool Is Intended For Educational And Authorized Testing Only.
Do Not Use It To Scan Websites Without Proper Permission.

---

## 💻 Built By [@DecryptMike](https://github.com/DecryptMike)

---

<p align="center">
  <img src="https://img.shields.io/badge/Built%20for-Cybersecurity-blue?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Made%20by-DecryptMike-green?style=for-the-badge"/>
</p>
