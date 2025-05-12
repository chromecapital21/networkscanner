# networkscanner
# network scanner written with python

# Network Scanner

A multi-threaded network scanner built in Python to detect active hosts and open ports on a network. This project demonstrates proficiency in socket programming, multi-threading, and command-line interface design.

## Features
- Scans a target IP for open ports within a specified range.
- Utilizes multi-threading for efficient scanning.
- Configurable port range, thread count, and timeout.
- Lightweight with no external dependencies.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/network-scanner.git


Navigate to the project directory:
cd network-scanner

Run the script (Python 3.x required):
python3 network_scanner.py --help

Usage

python3 network_scanner.py <target_ip> [--start-port <start>] [--end-port <end>] [--threads <threads>] [--timeout <timeout>]

Example

python3 network_scanner.py 192.168.1.1 --start-port 1 --end-port 1000 --threads 150 --timeout 0.5
