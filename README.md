# Network Scanning and Host Enumeration with Nmap

## Overview

This project demonstrates network scanning and host enumeration techniques using Nmap (Network Mapper). The objective is to discover active hosts, identify open ports, enumerate services, and gather system information within an authorized network environment.

## Objectives

- Discover active hosts on a network
- Identify open ports
- Detect running services and versions
- Perform operating system detection
- Generate scan reports
- Analyze network exposure

## Tools Used

- Nmap
- Linux / Windows
- Terminal / Command Prompt

## Features

### Host Discovery

```bash
nmap -sn 192.168.1.0/24
```

### Port Scanning

```bash
nmap -p- 192.168.1.10
```

### Service Enumeration

```bash
nmap -sV 192.168.1.10
```

### Operating System Detection

```bash
sudo nmap -O 192.168.1.10
```

### Aggressive Scan

```bash
sudo nmap -A 192.168.1.10
```

## Project Structure

```text
docs/
scans/
resources/
```

## Ethical Notice

This project is intended for educational purposes and authorized security assessments only. Always obtain permission before scanning any network or system.
