# 👁️ L0p4Map

Professional network monitoring & visualization framework built for security researchers, penetration testers, and network administrators.

---

# ⚡ Overview

**L0p4Map** combines high-speed ARP discovery, deep Nmap integration, and interactive topology visualization into a single modern interface.

Designed with a professional dark-themed UI using **PyQt6**, the project focuses on delivering fast and actionable network intelligence without unnecessary complexity.

---

# 🔥 Features

## 🌐 Network Discovery

* High-speed ARP scanning
* Local IEEE OUI vendor lookup
* Automatic hostname resolution
* NetBIOS & mDNS detection

## 🔎 Advanced Port Scanning

* Full Nmap integration
* SYN / UDP scanning
* Service & version detection
* OS fingerprinting
* NSE script support

## 🛡️ Security Enumeration

* HTTP banner grabbing
* SMB enumeration
* FTP/SSH detection
* SSL/TLS information gathering
* CVE & vulnerability lookup

## 📡 Network Intelligence

* Real-time traceroute
* Interactive topology graph
* Device relationship mapping
* Live monitoring support

## 🎨 Modern UI

* Dark professional interface
* Built with PyQt6
* Interactive graph visualization
* Export scan reports
* CSV & PNG graph export

---


# 🛠️ Requirements

* Linux (Debian / Arch recommended)
* Python 3.11+
* Nmap installed
* Root privileges

Install dependencies:

```bash
# Debian / Ubuntu
sudo apt install nmap python3-pip

# Arch Linux
sudo pacman -S nmap python-pip
```

---

# 📦 Installation

Clone the repository:

```bash
git clone https://github.com/HaxL0p4/L0p4Map.git
cd L0p4Map
python3 -m venv venv
source venv/bin/activate
```

Install Python requirements:

```bash
pip install -r requirements.txt
```

Make launcher executable:

```bash
sudo chmod +x L0p4Map.sh
```

---

# 🚀 Usage

Launch with root privileges:

```bash
sudo ./L0p4Map.sh
```

### Workflow

1. Select a network interface
2. Start ARP discovery scan
3. View detected devices
4. Run detailed port scans
5. Analyze topology graph
6. Export reports if needed

---


# ⚠️ Legal Disclaimer

This tool is intended for:

* Authorized security testing
* Internal network auditing
* Educational research

Unauthorized scanning or misuse may violate local laws and regulations.
Use responsibly.

