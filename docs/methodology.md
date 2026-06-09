# Methodology

## Phase 1: Network Reconnaissance

Identify the target network range.

Example:

```bash
nmap -sn 192.168.1.0/24
```

Purpose:
- Discover active hosts
- Determine reachable devices

---

## Phase 2: Port Scanning

Scan for open ports.

```bash
nmap -p- TARGET_IP
```

Purpose:
- Identify exposed services
- Detect attack surface

---

## Phase 3: Service Enumeration

Determine service versions.

```bash
nmap -sV TARGET_IP
```

Purpose:
- Identify software versions
- Detect outdated applications

---

## Phase 4: Operating System Detection

```bash
sudo nmap -O TARGET_IP
```

Purpose:
- Identify operating systems
- Improve asset inventory

---

## Phase 5: Comprehensive Assessment

```bash
sudo nmap -A TARGET_IP
```

Includes:
- OS detection
- Service detection
- NSE scripts
- Traceroute

---

## Documentation

Save all scan results and screenshots for analysis.
