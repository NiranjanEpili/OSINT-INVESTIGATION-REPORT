<div align="center">

# 🔍 OSINT Investigation Tool

### Advanced Website Reconnaissance & Security Analysis Platform

[![Python Version](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey.svg)](https://github.com)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com)

[Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [Documentation](#-documentation)

![OSINT Tool Banner](https://via.placeholder.com/800x200/667eea/ffffff?text=OSINT+Investigation+Tool)

</div>

---

A comprehensive, professional-grade cybersecurity tool with **20+ investigation features**, dual-mode interface (Browser + Desktop), and beautiful PDF reports for security analysis and OSINT gathering.

---

## 📋 Table of Contents

- [🌟 Overview](#-overview)
- [✨ Key Features](#-key-features)
- [📸 Screenshots](#-screenshots)
- [🚀 Installation](#-installation)
- [🎯 Quick Start](#-quick-start)
- [📖 Usage Guide](#-usage-guide)
- [🔬 Advanced Features](#-advanced-features)
- [🏗️ Architecture](#-architecture)
- [📚 Documentation](#-documentation)
- [⚠️ Ethical Use](#%EF%B8%8F-ethical-use--legal-disclaimer)
- [🤝 Contributing](#-contributing)
- [🏆 Acknowledgments](#-acknowledgments)

---

## 🌟 Overview

**OSINT Investigation Tool** is a comprehensive, dual-mode platform for gathering and analyzing open-source intelligence on websites. Built with Python, it combines powerful reconnaissance capabilities with an intuitive interface, making it perfect for security researchers, students, and professionals.

### 🎯 Why Choose This Tool?

<div align="center">

| Feature | Description |
|---------|-------------|
| 🌐 **Dual Mode** | Browser-based web interface + Traditional desktop GUI |
| 🔍 **20+ Features** | Comprehensive investigation capabilities |
| 📄 **Beautiful Reports** | Professional PDF exports with security scoring |
| 🔒 **Security Analysis** | Advanced security header analysis and scoring |
| 🚀 **Fast & Efficient** | Multi-threaded scanning for optimal performance |
| 🎓 **Educational** | Perfect for learning OSINT techniques |

</div>

---

## ✨ Key Features

### 🔎 Investigation Capabilities

<table>
<tr>
<td width="50%">

#### Basic OSINT
- ✅ **WHOIS Information**
  - Domain registration details
  - Registrar information
  - Expiration dates
- ✅ **DNS Analysis**
  - A, AAAA, MX, NS records
  - TXT, CNAME, SOA records
- ✅ **SSL/TLS Inspection**
  - Certificate validation
  - Issuer information
  - Expiry dates

</td>
<td width="50%">

#### Advanced Features
- 🔌 **Port Scanning**
  - 21 common ports
  - Service identification
- 🔒 **Security Headers**
  - 8 header analysis
  - Security score (0-100%)
- 🤖 **CMS Detection**
  - WordPress, Joomla, Drupal
  - Shopify, Wix, Magento

</td>
</tr>
</table>

### 🎨 Interface Options

<div align="center">

| Mode | Description | Best For |
|------|-------------|----------|
| 🌐 **Browser Mode** | Modern web interface with real-time updates | Remote access, modern UI |
| 💻 **Desktop Mode** | Tkinter-based GUI with 11 organized tabs | Offline use, traditional interface |

</div>

### 📊 Additional Intelligence

<details>
<summary><b>🌐 Network Intelligence</b></summary>

- IP Geolocation & mapping
- Reverse DNS lookup
- ISP & organization identification
- Hosting provider detection
- Server fingerprinting

</details>

<details>
<summary><b>📝 Content Analysis</b></summary>

- Meta tags extraction (all types)
- Open Graph & Twitter Card data
- Email & phone harvesting
- robots.txt parsing
- Sitemap discovery

</details>

<details>
<summary><b>📱 Social Intelligence</b></summary>

- Facebook profiles/pages
- Twitter accounts
- Instagram profiles
- LinkedIn company pages
- YouTube channels
- GitHub repositories

</details>

---

## 📸 Screenshots

<div align="center">

### 🌐 Browser Mode Interface
![Browser Mode](https://via.placeholder.com/700x350/667eea/ffffff?text=Modern+Web+Interface)

### 💻 Desktop Mode GUI
![Desktop Mode](https://via.placeholder.com/700x350/764ba2/ffffff?text=Professional+Desktop+GUI)

### 📊 Security Analysis
![Security Analysis](https://via.placeholder.com/700x350/4caf50/ffffff?text=Security+Score+Dashboard)

### 📄 PDF Report Sample
![PDF Report](https://via.placeholder.com/700x350/ff9800/ffffff?text=Beautiful+PDF+Reports)

</div>

---

## 🚀 Installation

### Prerequisites

- **Python 3.7+** - [Download Here](https://www.python.org/downloads/)
- **pip** - Package installer (included with Python)
- **Internet Connection** - For package installation and scanning

### 📦 Quick Install

```bash
# Clone the repository
git clone https://github.com/yourusername/osint-investigation-tool.git

# Navigate to directory
cd osint-investigation-tool

# Install dependencies
pip install -r requirements.txt

# Create required directories
python setup_dirs.py

# Fix WHOIS package (if needed)
python COMPLETE_FIX.py
```

### Manual Installation

```bash
# Install packages individually
pip install flask python-whois requests beautifulsoup4
pip install reportlab dnspython validators
```

### ✅ Verify Installation

```bash
# Test all imports
python test_imports.py
```

---

## 🎯 Quick Start

### Method 1: Easy Launch (Recommended)

```bash
# Windows
START.bat

# Linux/Mac
python enhanced_launch.py
```

**Choose your mode:**
```
┌─────────────────────────────────────┐
│  OSINT Investigation Tool           │
├─────────────────────────────────────┤
│  [1] 🌐 Browser Mode                │
│  [2] 💻 Desktop Mode                │
│  [3] ❌ Exit                         │
└─────────────────────────────────────┘
```

### Method 2: Direct Launch

#### 🌐 Browser Mode
```bash
python web_app.py
# Then open: http://localhost:5000
```

#### 💻 Desktop Mode
```bash
python enhanced_osint_tool.py
```

---

## 📖 Usage Guide

### Basic Workflow

1. **Launch** the tool (Browser or Desktop mode)
2. **Enter** target URL (e.g., `https://example.com`)
3. **Start** investigation and wait 30-90 seconds
4. **Browse** results in organized tabs
5. **Export** as professional PDF or JSON

### Browser Mode Steps

1. Start browser mode: `python web_app.py`
2. Open `http://localhost:5000` in browser
3. Enter target URL
4. Click "Start Investigation"
5. Monitor real-time progress
6. View results and export

### Desktop Mode Steps

1. Launch: `python enhanced_osint_tool.py`
2. Enter URL in input field
3. Click "▶ Start Investigation"
4. Browse 11 organized tabs
5. Export reports

---

## 🔬 Advanced Features

### 🔒 Security Scoring System

<div align="center">

| Score Range | Level | Description |
|-------------|-------|-------------|
| 75-100% 🟢 | **Excellent** | Strong security posture |
| 50-74% 🟡 | **Good** | Adequate protection |
| 25-49% 🟠 | **Fair** | Needs improvement |
| 0-24% 🔴 | **Poor** | Critical issues |

</div>

### 🔌 Port Scanning

Scans **21 common ports**:
```
HTTP (80, 8080)    HTTPS (443, 8443)    SSH (22)    
FTP (21)           SMTP (25)            DNS (53)
MySQL (3306)       PostgreSQL (5432)    RDP (3389)
And more...
```

### 🎨 Technology Detection

Identifies **50+ technologies**:
- Web servers (Apache, Nginx, IIS)
- CMS platforms (WordPress, Joomla, Drupal)
- JavaScript frameworks (React, Vue, Angular)
- Analytics & CDNs

---

## 🏗️ Architecture

### Project Structure

```
osint-investigation-tool/
│
├── 📁 Core Application
│   ├── enhanced_launch.py          # Main launcher
│   ├── enhanced_osint_tool.py      # Desktop GUI
│   ├── web_app.py                  # Web interface
│   ├── advanced_scanner.py         # Investigation engine
│   └── enhanced_pdf.py             # PDF generator
│
├── 📁 Configuration
│   ├── requirements.txt            # Dependencies
│   └── setup_dirs.py              # Directory setup
│
├── 📁 Documentation
│   ├── README.md                  # This file
│   ├── QUICK_START_GUIDE.md       # Quick start
│   └── README_ENHANCED.md         # Complete docs
│
└── 📁 Reports
    └── (Generated PDF/JSON reports)
```

### Technology Stack

| Component | Technology |
|-----------|------------|
| **Backend** | Python 3.7+ |
| **Web Framework** | Flask |
| **GUI Framework** | Tkinter |
| **PDF Generation** | ReportLab |
| **Web Scraping** | BeautifulSoup4 |

---

## 📚 Documentation

### Available Guides

- 📘 [README_ENHANCED.md](README_ENHANCED.md) - Complete documentation
- 📗 [QUICK_START_GUIDE.md](QUICK_START_GUIDE.md) - Step-by-step tutorial
- 📙 [TROUBLESHOOTING_HINDI.txt](TROUBLESHOOTING_HINDI.txt) - Hindi troubleshooting
- 📕 [BROWSER_MODE_FIX.txt](BROWSER_MODE_FIX.txt) - Browser mode fixes

---

## ⚠️ Ethical Use & Legal Disclaimer

### 📜 Important Notice

This tool is designed for **EDUCATIONAL** and **AUTHORIZED TESTING** purposes only.

### ✅ Acceptable Use

- ✓ Testing your own websites
- ✓ Authorized security assessments
- ✓ Academic research and learning
- ✓ Penetration testing with permission

### ❌ Prohibited Use

- ✗ Unauthorized access attempts
- ✗ Malicious activities
- ✗ Privacy violations
- ✗ Any unlawful activities

**YOU are responsible for how you use this tool.**

---

## 🎓 Use Cases

| Use Case | Description |
|----------|-------------|
| 🔒 **Security Assessments** | Evaluate website security posture |
| 🏢 **Competitive Analysis** | Understand competitor tech stack |
| 🕵️ **Digital Forensics** | Gather digital evidence |
| 🎯 **Threat Intelligence** | Identify potential threats |
| 📚 **Academic Research** | Learn OSINT techniques |

---

## 🐛 Known Issues & Fixes

<details>
<summary><b>WHOIS Error Fix</b></summary>

```bash
pip uninstall whois -y
pip install python-whois
```
Or run: `python COMPLETE_FIX.py`

</details>

<details>
<summary><b>Browser Mode Issues</b></summary>

```bash
# Install Flask
pip install flask

# Test browser mode
python test_browser_mode.py

# Or use Desktop Mode (easier)
python enhanced_launch.py → Option 2
```

</details>

---

## 🤝 Contributing

Contributions welcome! Here's how:

1. **Fork** the repository
2. **Create** a feature branch
3. **Commit** your changes
4. **Push** to the branch
5. **Open** a Pull Request

---

## 📊 Statistics

<div align="center">

![Features](https://img.shields.io/badge/features-20%2B-brightgreen)
![Lines of Code](https://img.shields.io/badge/lines%20of%20code-2500%2B-blue)
![Dependencies](https://img.shields.io/badge/dependencies-8-orange)

### Investigation Capabilities

| Category | Count |
|----------|-------|
| **Scan Types** | 20+ |
| **Ports Scanned** | 21 |
| **Security Headers** | 8 |
| **CMS Detected** | 6+ |
| **Export Formats** | 2 |

</div>

---

## 🏆 Acknowledgments

### Built With
- [Python](https://www.python.org/) - Core language
- [Flask](https://flask.palletsprojects.com/) - Web framework
- [ReportLab](https://www.reportlab.com/) - PDF generation
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) - Web scraping

---

## 📝 License

This project is licensed under the **MIT License**.

---

## 📞 Support

### Getting Help

- 📖 Check [Documentation](README_ENHANCED.md)
- 🐛 Report Issues
- 💬 Community Discussions

---

<div align="center">

### Made with ❤️ for the Security Community

**[⬆ Back to Top](#-osint-investigation-tool)**

---

© 2024 OSINT Investigation Tool | [Documentation](README_ENHANCED.md) | [Quick Start](QUICK_START_GUIDE.md)

</div>
