#R NANDA KISHORE - cybersecurity-Assignment-3
Python-based automation of Ping, ARP, and Nmap network scanning tools

#Network Scanning Tools

#Project Description

This project is developed to understand basic network scanning using Python. It includes three tools: Ping Scanner, ARP Scanner, and Nmap Scanner. These tools help in checking connectivity, identifying devices in a network, and scanning open ports and services.

---

#How to Install Nmap

Install Nmap using Homebrew:

#bash
brew install nmap

Verify installation:

#bash
nmap -V

#How to Run Programs

Ping Scanner

#bash
python3 ping_scanner.py

ARP Scanner

#bash
python3 arp_scanner.py

Nmap Scanner

#bash
python3 nmap_scanner.py


Example Usage

Ping Scanner

Input:
google.comg
Output:

* Host is reachable
* Average response time displayed

ARP Scanner

Output:

* Displays IP and MAC address
* Shows total number of devices

Nmap Scanner

Input:
google.com

Options:
1. Host Discovery
2. Port Scan
3. Custom Port Range
4. Service Detection
5. OS Detection

Output:
Shows open ports and services

Screenshots
Screenshots are available in the **screenshots/** folder:

* ping_output.png
* arp_output.png
* nmap_output.png

Project Structure
network-scanning-tools/
|
|--ping_scanner.py
├── arp_scanner.py
├── nmap_scanner.py
├── README.md
│
└── screenshots/
    ├── ping_output.png
    ├── arp_output.png
    ├── nmap_output.png
Conclusion
This project demonstrates how Python can be used to automate network scanning tools like ping, ARP, and
