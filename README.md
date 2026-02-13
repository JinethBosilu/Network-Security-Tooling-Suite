# Network Security Tooling Suite

A curated collection of educational network security tools built to explore ARP behavior, packet inspection, MAC manipulation, and spoof detection in controlled lab environments.

This repository serves as a structured index of related projects focused on understanding low-level networking protocols and defensive detection mechanisms.

---

## Purpose

The goal of this toolkit is to:

- Understand ARP protocol mechanics
- Explore MAC address manipulation
- Analyze packet-level traffic behavior
- Study MITM concepts in controlled lab environments
- Implement defensive detection techniques against ARP spoofing

All tools are intended strictly for educational use within networks you own or have explicit permission to test.

---

## Included Projects

### 1️⃣ ARP Network Scanner
🔗 https://github.com/JinethBosilu/Network_scanner

- Discovers active hosts on a local subnet using crafted ARP requests.
- Displays IP ↔ MAC mappings.
- Built using Scapy.

---

### 2️⃣ ARP Spoofing Demonstration Script
🔗 https://github.com/JinethBosilu/arp_spoofing

- Demonstrates ARP cache poisoning mechanics in a controlled lab.
- Restores ARP tables on termination.
- Used to understand Layer 2 MITM positioning.

---

### 3️⃣ ARP Spoof Detection Tool
🔗 https://github.com/JinethBosilu/arpspoof_detecter

- Monitors ARP replies and validates MAC ↔ IP consistency.
- Detects potential ARP cache poisoning attempts.
- Defensive-focused implementation.

---

### 4️⃣ Packet Sniffer (HTTP Inspector)
🔗 https://github.com/JinethBosilu/packet_sniffer

- Captures traffic on a specified interface.
- Extracts HTTP request URLs and inspects payload data.
- Demonstrates packet parsing fundamentals.

---

### 5️⃣ MAC Address Changer
🔗 https://github.com/JinethBosilu/mac_changer

- CLI tool to modify network interface MAC addresses.
- Uses system networking commands via subprocess execution.
- Includes argument parsing and privilege handling.

---

## Technical Concepts Covered

- ARP protocol structure and behavior
- MAC ↔ IP mapping validation
- Layer 2 MITM mechanics
- Packet capture and inspection
- Linux interface management
- CLI argument parsing and subprocess control

---

## Security & Ethics

This toolkit:

- Does NOT exploit remote systems
- Does NOT perform brute force attacks
- Does NOT target live internet infrastructure
- Is limited to local lab experimentation

Always ensure explicit authorization before performing network testing.

---

## Author

Jineth Bosilu  
Computer Science Undergraduate — Cybersecurity & Secure Systems
