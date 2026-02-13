# Network Security Tooling Suite

A curated collection of educational network security tools built to explore ARP behavior, packet inspection, MAC manipulation, and spoof detection in controlled lab environments.

This project focuses on understanding low-level networking protocols and defensive detection mechanisms — not offensive exploitation.

---

## Purpose

The goal of this toolkit is to:

- Understand ARP protocol mechanics
- Explore MAC address manipulation
- Analyze packet-level traffic behavior
- Study MITM concepts in controlled environments
- Implement defensive detection techniques against ARP spoofing

All tools are intended for educational use within networks you own or have explicit permission to test.

---

## Tools Included

### 1️⃣ ARP Network Scanner
- Discovers active hosts on a local subnet using crafted ARP requests.
- Displays IP ↔ MAC mappings.
- Built using Scapy.

---

### 2️⃣ ARP Spoofing Demonstration Script
- Demonstrates ARP cache poisoning mechanics in a controlled lab.
- Restores ARP tables on termination.
- Used to understand MITM positioning at Layer 2.

---

### 3️⃣ ARP Spoof Detection Tool
- Monitors ARP replies and validates MAC ↔ IP consistency.
- Detects potential ARP cache poisoning attempts.
- Defensive-focused implementation.

---

### 4️⃣ Packet Sniffer (HTTP Inspector)
- Captures network traffic on a specified interface.
- Extracts HTTP request URLs.
- Demonstrates payload inspection techniques.

---

### 5️⃣ MAC Address Changer
- CLI tool to modify network interface MAC addresses.
- Uses system networking commands via subprocess execution.
- Includes argument parsing and privilege handling.

---

## Technical Stack

- Python 3
- Scapy
- Linux Networking (ARP, TCP/IP)
- Subprocess & CLI Argument Parsing
- Packet Capture Concepts

---

## Security & Ethics

This toolkit:

- Does NOT exploit remote systems
- Does NOT brute force credentials
- Does NOT scan live internet targets
- Is limited to local lab experimentation

Always ensure you have explicit authorization before running network-level experiments.

---

## Learning Outcomes

Through this project, the following concepts were explored:

- ARP request/response structure
- Layer 2 MITM mechanics
- Packet inspection fundamentals
- IP ↔ MAC mapping validation
- Linux interface management

---

## Author

Jineth Bosilu  
Computer Science Undergraduate — Cybersecurity & Secure Systems
