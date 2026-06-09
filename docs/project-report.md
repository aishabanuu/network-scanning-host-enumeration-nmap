# Project Report

## Abstract

Network scanning is an essential phase of network administration and security assessment. This project uses Nmap to identify active hosts, open ports, running services, and operating systems on authorized networks.

## Introduction

Nmap is a widely used network discovery and auditing tool that helps security professionals analyze network infrastructure.

## Objectives

1. Discover hosts.
2. Enumerate services.
3. Detect operating systems.
4. Generate reports.

## Methodology

### Phase 1: Host Discovery

```bash
nmap -sn 192.168.1.0/24
```

### Phase 2: Port Scanning

```bash
nmap -p- TARGET_IP
```

### Phase 3: Service Enumeration

```bash
nmap -sV TARGET_IP
```

### Phase 4: OS Detection

```bash
sudo nmap -O TARGET_IP
```

## Results

Record:

| Host | Open Ports | Services | OS |
|--------|----------|----------|----|
| Example | Example | Example | Example |

## Conclusion

The project successfully demonstrated host discovery and service enumeration using Nmap.
