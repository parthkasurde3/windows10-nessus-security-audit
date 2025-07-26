# 🚨Vulnerability Assessment on a Windows Machine using Nessus

## 📖Overview
This project conducts a comprehensive vulnerability assessment on a Windows virtual machine using the Nessus vulnerability scanner. The scan identifies various levels of system vulnerabilities including critical, high, medium, and low severity issues.

## 🛠️Tools Used
- **Nessus** by Tenable for vulnerability scanning
- **Windows VM** as the target environment

## 🔑Key Findings
The vulnerability assessment scan on the target Windows 10 system revealed a range of issues including:
- **Critical vulnerabilities** like MS17-010 (EternalBlue)
- **High-risk vulnerabilities** associated with outdated Windows SMB services
- **Medium-level issues** such as TLS/SSL weak ciphers
- **Low-level information disclosure** risks

For detailed breakdown and analysis, refer to the files in the `docs/` and `logs/` folders.

## 📁Folder Structure
```
.
├── LICENSE
├── README.md
├── .gitignore
├── docs/
│   ├── WINDOWS10_NESSUS_REPORT.pdf
│   ├── summary.txt
├── logs/
│   └── nessus_scan_log.txt
```

## License
This project is licensed under the MIT License.
