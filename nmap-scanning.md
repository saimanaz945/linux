# Nmap Scanning Commands

A collection of useful Nmap commands for beginners in Cybersecurity and Ethical Hacking.

---

## 1. Scan a Single IP
Scans a single target device for open ports.

```bash
nmap 192.168.1.1
```

---

## 2. Scan a Website or Domain
Scans a website/domain for active services and open ports.

```bash
nmap google.com
```

---

## 3. Scan Multiple IP Addresses
Scans multiple target systems at the same time.

```bash
nmap 192.168.1.1 192.168.1.2
```

---

## 4. Scan an IP Range
Scans all IP addresses within the specified range.

```bash
nmap 192.168.1.1-100
```

---

## 5. Scan an Entire Subnet
Scans every device connected in the subnet.

```bash
nmap 192.168.1.0/24
```

---

## 6. Scan a Specific Port
Scans only the specified port on the target machine.

```bash
nmap -p 80 192.168.1.1
```

---

## 7. Scan Multiple Ports
Scans selected ports on the target.

```bash
nmap -p 21,22,80,443 192.168.1.1
```

---

## 8. Scan All Ports
Scans all 65535 TCP ports.

```bash
nmap -p- 192.168.1.1
```

---

## 9. Fast Scan
Performs a faster scan using only common ports.

```bash
nmap -F 192.168.1.1
```

---

## 10. Service Version Detection
Detects versions of running services on open ports.

```bash
nmap -sV 192.168.1.1
```

---

## 11. Operating System Detection
Attempts to identify the operating system of the target.

```bash
nmap -O 192.168.1.1
```

---

## 12. Aggressive Scan
Enables OS detection, service detection, NSE scripts, and traceroute.

```bash
nmap -A 192.168.1.1
```

---

## 13. SYN Stealth Scan
Performs a stealthy TCP SYN scan that is faster and less detectable.

```bash
nmap -sS 192.168.1.1
```

---

## 14. TCP Connect Scan
Uses a full TCP connection to scan ports.

```bash
nmap -sT 192.168.1.1
```

---

## 15. UDP Scan
Scans UDP ports on the target system.

```bash
nmap -sU 192.168.1.1
```

---

## 16. Ping Scan
Discovers live hosts without scanning ports.

```bash
nmap -sn 192.168.1.0/24
```

---

## 17. Save Output to File
Saves scan results into a text file.

```bash
nmap -oN result.txt 192.168.1.1
```

---

## 18. Verbose Mode
Displays detailed scanning progress and information.

```bash
nmap -v 192.168.1.1
```

---

## 19. Vulnerability Scan Using NSE
Runs Nmap vulnerability detection scripts.

```bash
nmap --script vuln 192.168.1.1
```

---

## 20. Timing Template Scan
Increases scanning speed using aggressive timing.

```bash
nmap -T4 192.168.1.1
```

---

# Timing Levels

| Option | Description |
|--------|-------------|
| `-T0` | Paranoid |
| `-T1` | Sneaky |
| `-T2` | Polite |
| `-T3` | Normal |
| `-T4` | Aggressive |
| `-T5` | Insane |

---

# Install Nmap

```bash
sudo apt install nmap
```

---

# Disclaimer

This project is for educational and ethical hacking purposes only.

Do not scan systems without permission.
[Nmap Scanning Report](./Nmap_Scanning_Report.pdf)

