# Recon Automation Tool

Python-based reconnaissance automation framework for bug bounty hunting and web application security testing.

## Features

- Subdomain Enumeration
- Live Host Detection
- URL Collection
- Katana Crawling
- JS Extraction

## Requirements

- Python 3
- subfinder
- httpx
- katana
- gau
- waybackurls

## Installation

```bash
git clone https://github.com/tejassroot/recon-automation-tool.git
cd recon-automation-tool
chmod +x recon
sudo cp recon /usr/local/bin/recon

```

## Usage

```bash
./recon -d example.com
```

## Output Structure

```text
example.com/
├── subdomains/
├── live_hosts/
├── urls/
├── crawl/
├── js/
└── interesting/
```

## Disclaimer

This tool is intended for authorized security testing and bug bounty programs only.
