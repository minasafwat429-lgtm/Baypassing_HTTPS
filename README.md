# Packet Injector - HTTP Injection Tool

Advanced tool for injecting code into HTTP packets using Man-in-the-Middle (MITM) technique via NetfilterQueue.

## ⚠️ Disclaimer

This tool is for educational purposes only. Using it on networks without explicit permission is illegal. The user assumes full responsibility.

## 🎯 Features

- Intercept and modify HTTP packets in real-time
- Remove `Accept-Encoding` from requests for better readability
- Upgrade `HTTP/1.1` to `HTTP/1.0` to prevent compression
- Inject JavaScript code into HTML pages
- Automatically recalculate content length
- Process both requests and responses on port 8080

## 📋 Requirements

- Linux (with NetfilterQueue support)
- Python 3.6+
- Root privileges

## 🔧 Installation

```bash
# Install required packages
pip install -r requirements.txt

# Install NetfilterQueue dependencies (for Linux)
sudo apt-get install build-essential python3-dev libnetfilter-queue-dev

# Reinstall NetfilterQueue properly
pip uninstall netfilterqueue
pip install --no-cache-dir netfilterqueue
