# internet-speed-test-cli
A lightweight CLI tool for measuring internet speed with support for automation, multiple output formats (JSON/CSV), and advanced metrics including jitter and latency.
# Internet Speed Test CLI 🚀

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Tests](https://github.com/YOUR_USERNAME/internet-speed-test-cli/workflows/CI/badge.svg)](https://github.com/YOUR_USERNAME/internet-speed-test-cli/actions)

A lightweight, cross-platform Command-Line Interface tool for measuring internet speed with advanced features for automation, monitoring, and data analysis.

## ✨ Features

- 📊 **Comprehensive Metrics**: Download/upload speeds, latency, jitter
- 🤖 **Automation Ready**: Perfect for cron jobs and CI/CD pipelines
- 💾 **Multiple Output Formats**: Text, JSON, CSV for easy integration
- 🎯 **Server Selection**: Auto-select optimal servers or choose manually
- 📈 **Historical Logging**: Track performance over time with SQLite
- 🔧 **Lightweight**: Minimal dependencies, fast execution
- 🌍 **Cross-Platform**: Works on Windows, macOS, and Linux

## 📦 Installation

### From PyPI (Coming Soon)
```bash
pip install netspeed-cli
```

### From Source
```bash
git clone https://github.com/YOUR_USERNAME/internet-speed-test-cli.git
cd internet-speed-test-cli
pip install -r requirements.txt
python setup.py install
```

## 🎯 Quick Start

### Basic Speed Test
```bash
netspeed
```

### Export to JSON
```bash
netspeed --json output.json
```

### Export to CSV
```bash
netspeed --csv results.csv
```

### Select Specific Server
```bash
netspeed --server 12345
```

### Enable Logging
```bash
netspeed --log history.db
```

## 📖 Usage
