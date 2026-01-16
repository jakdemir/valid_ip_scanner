# Valid IP Scanner

A Java tool to scan IP address ranges and identify responding hosts.

## Overview

This project scans a range of IP addresses and returns information about which addresses are active/responding.

## Features

- Scan IP address ranges
- Identify active hosts
- Report response status

## Technologies

- Java
- Network programming
- ICMP/TCP scanning

## Usage

```java
IPScanner scanner = new IPScanner();
List<String> activeHosts = scanner.scanRange("192.168.1.1", "192.168.1.255");
```

## ⚠️ Disclaimer

Only scan networks you own or have explicit permission to scan. Unauthorized network scanning may be illegal.

## Author

Jak Akdemir
