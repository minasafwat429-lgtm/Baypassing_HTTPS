<div align="center">
  <h1>🛡️ HTTP Packet Injector</h1>
  <p><strong>Advanced HTTP Traffic Manipulation & Packet Injection Tool</strong></p>
  
  [![Python Version](https://img.shields.io/badge/python-3.8+-blue.svg)](https://python.org)
  [![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
  [![Platform](https://img.shields.io/badge/platform-Linux-red.svg)](https://linux.org)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
</div>

## ⚠️ Legal Disclaimer

> **IMPORTANT:** This tool is for **educational purposes only**. Use only on networks you own or have explicit written permission to test. Unauthorized interception of network traffic is illegal in most jurisdictions. The authors assume no liability for misuse.

## 🎯 Features

- 🔍 **Real-time HTTP Traffic Interception**
- 💉 **JavaScript Code Injection** into HTML responses
- 📊 **Automatic Content-Length Recalculation**
- 🔄 **HTTP Version Downgrade** (2.0/1.1 → 1.0)
- 🚫 **Remove Compression Headers** for better injection
- 🎯 **Port-specific Filtering** (Customizable)
- 🛡️ **Error Handling & Recovery**
- 📝 **Detailed Logging System**

## 📋 Prerequisites

- **Operating System:** Linux (Kali, Ubuntu, Debian)
- **Python Version:** 3.8 or higher
- **Root Privileges:** Required for packet manipulation
- **Network:** Target network access

## 🚀 Quick Installation

### Method 1: Direct Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/HTTP-Packet-Injector.git
cd HTTP-Packet-Injector

# Run installation script
chmod +x scripts/setup.sh
sudo ./scripts/setup.sh

bash
# Build Docker image
