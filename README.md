# Sec-Headers

Sec-Headers is a lightweight, cross-platform command-line security scanner designed for rapid assessment of HTTP security headers, SSL/TLS configuration, certificate integrity, and backend technology disclosure.

The tool is built for security professionals, penetration testers, auditors, and blue team practitioners who require fast, dependency-free analysis of web security posture.

---

## 🚀 Key Features

✔ Security Headers Analysis  
✔ SSL Certificate Intelligence  
✔ Weak Certificate Detection  
✔ TLS Session Details  
✔ Backend Technology Detection  
✔ Colorized Tabular CLI Output  
✔ Insecure TLS Mode for Internal Assessments  

---

## 🖥 Supported Platforms

✔ Windows  
✔ Linux  
✔ macOS (Intel & Apple Silicon)  

No runtime dependencies required.

Users only need to download the binary and execute.

---

## 📌 Usage

sec-headers <domain>

Examples:

sec-headers example.com  
sec-headers https://example.com  
sec-headers internal-app.local --insecure  

---

## 🔍 Security Checks Performed

### ✅ Security Headers
• Strict-Transport-Security  
• Content-Security-Policy  
• X-Frame-Options  
• X-Content-Type-Options  
• Referrer-Policy  
• Permissions-Policy  

---

### ✅ SSL Certificate Analysis
• Issuer & Subject Details  
• Certificate Validity  
• Expiry Detection  
• Signature Algorithm Strength  
• Public Key Size Evaluation  

---

### ✅ TLS Session Analysis
• Negotiated TLS Version  
• Cipher Suite Detection  
• Deprecated Protocol Identification  

---

### ✅ Backend Technology Detection
• Server Header Disclosure  
• X-Powered-By Analysis  

---

## ⚠ Insecure TLS Mode

For internal environments using self-signed certificates:

sec-headers <domain> --insecure

This bypasses TLS certificate validation.

---

## 🎯 Intended Use Cases

✔ Penetration Testing  
✔ Red Team Reconnaissance  
✔ Security Audits  
✔ Compliance Assessments  
✔ Attack Surface Mapping  
✔ Quick Web Security Validation  

---

## 🛡 Disclaimer

This tool is intended for authorized security testing, defensive security research, and educational purposes only.

Users are responsible for complying with applicable laws and obtaining proper authorization before scanning any systems.

---

## 📄 License

MIT License
