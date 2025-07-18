# darkboss1-ip-portscan

A darkboss1 Python-based TCP port scanner that allows you to scan one or more target IP addresses or domain names for open ports within a specified range. This tool provides information about open ports, including service banners and potential vulnerabilities.


## Features

- Scan one or more target IP addresses or domain names for open ports.
- Specify a port range to scan or scan all available ports.
- Retrieve service banners and service versions for open ports.
- Detect known vulnerabilities for specific services (e.g., FTP, SSH).
- Multithreaded scanning for faster results.
- Save scan results to a JSON file.
- Optional verbose output.


## Getting Started

### Must Install

- Python 3.x
- pip (Python package manager)

### Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/darkboss1/darkboss1-ip-portscan.git
  
2. Navigate to the project directory:
   ```shell  
   cd darkboss1-ip-portscan
3. Install the required Python packages:
   ```shell
   pip install -r requirements.txt 
## Usage    
```bash
python darkboss1-ip-portscan.py -t <targets> [-p <port-range>] [-T <timeout>] [-n <num-threads>] [-o <output>] [-v]
```
## Examples
1. Scan a single target for open ports (default port range):
 ```shell
 python darkboss1-ip-portscan.py -t 192.168.1.1
 ```
2. Scan multiple targets with a custom port range and save results to a file:
```shell
 python darkboss1-ip-portscan.py -t example.com 192.168.1.1 -p 1-65535 -o results.json
``` 
3. Enable verbose output:
```shell
python darkboss1-ip-portscan.py -t 192.168.1.1 -v
```
## Purpose

The purpose of this project is to provide a simple yet effective TCP port scanning tool that allows users to scan one or more target IP addresses or domain names for open ports. It is designed to be versatile, fast, and informative, providing essential information about open ports, service banners, and potential vulnerabilities. Whether you are a network administrator, a security professional, or a curious individual, this tool can help you identify open ports on your network and gather valuable insights about the services running on them.
## Contact
Telegram: https://t.me/darkboss1bd
