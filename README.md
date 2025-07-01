🔍 Nessus Essentials – Windows Vulnerability Scan
📦 Requirements
Windows 10/11 (Admin access)

Nessus Essentials

⚙️ Setup Instructions
Download & Install Nessus Essentials
→ Select "Nessus Essentials", get free activation key
→ Access via https://localhost:8834

Initial Setup
→ Enter activation key
→ Let plugins download (~15 min)

Create & Launch Scan
→ New Scan → Basic Network Scan
→ Target: 127.0.0.1 (local machine)
→ Launch and wait (~30–60 mins)

Review Results
→ Check Critical/High vulnerabilities
→ Export report (PDF/HTML)

🔧 Fixing Common Vulnerabilities
Vulnerability	Fix Command / Action
SMBv1 Enabled	Disable-WindowsOptionalFeature -Online -FeatureName SMB1Protocol
Missing Updates	Run Windows Update
Weak RDP Configuration	Enable NLA or Disable RDP
Outdated Apps (Java, etc.)	Uninstall or update

📸 Optional
Take screenshots of scan summary & key vulnerabilities

Document actions taken to fix issues

✅ Best Practices
Run monthly scans

Keep Windows updated

Remove unused/vulnerable software

Use Defender or another AV
