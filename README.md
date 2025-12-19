# CodeAlpha – Port Scanner (Cybersecurity Internship)

This project is developed as **Task 3** of the **CodeAlpha Cybersecurity Internship**.  
It is a Python-based **Port Scanner** that scans a target system to identify open network ports.

---

##  Project Overview

The Port Scanner checks a range of ports on a given IP address or hostname to determine which ports are open and accepting connections.  
This is a fundamental cybersecurity task used in network auditing and vulnerability assessment.

---

##  Features

- Scans a user-defined range of ports  
- Identifies open ports on a target system  
- Uses TCP socket connections  
- Simple and beginner-friendly  
- Works on Ubuntu / WSL  

---

##  Technologies Used

- Python 3  
- Socket Programming  
- Ubuntu (WSL)  
- Git & GitHub  

---

##  Installation

1. Clone the repository:
- git clone https://github.com/srl9064/CodeAlpha_PortScanner.git
- cd CodeAlpha_PortScanner

2. Create and activate a virtual environment:
- python3 -m venv venv
- source venv/bin/activate

---

##  How to Run

Run the port scanner using:
python3 port_scanner.py

---

##  Sample Output
Enter target IP or hostname: 127.0.0.1
Enter start port: 20
Enter end port: 100

Scanning 127.0.0.1 from port 20 to 100
Port 22 is OPEN
Port 80 is OPEN
