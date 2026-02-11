# Comprehensive Networking Commands for Learning

This document provides a collection of useful networking commands that can help you in learning and performing network-related tasks.

## Basic Networking Commands

### 1. Check IP Address
- **Windows:** `ipconfig`
- **Linux/macOS:** `ifconfig` or `ip addr`

### 2. Check Network Connectivity
- **Ping:** `ping <hostname_or_IP>`

### 3. Show Routing Table
- **Windows:** `route print`
- **Linux/macOS:** `route -n`

### 4. View Open Ports
- **Windows:** `netstat -ano`
- **Linux:** `netstat -tuln`

### 5. Traceroute Command
- **Windows:** `tracert <hostname>`
- **Linux/macOS:** `traceroute <hostname>`

## DNS Commands

### 6. Query DNS Records
- **Windows:** `nslookup <domain>`
- **Linux/macOS:** `dig <domain>`

### 7. Flush DNS Cache
- **Windows:** `ipconfig /flushdns`
- **Linux:** `systemd-resolve --flush-caches`

## Advanced Networking Commands

### 8. Network Interface Configuration
- **Linux:** `nmcli`, `nmtui`

### 9. Monitor Network Traffic
- **Linux:** `tcpdump`, `wireshark`

### 10. File Transfer
- **Linux:** `scp`, `sftp`

## Conclusion

These commands are just the tip of the iceberg in terms of networking. Keep exploring and practicing to deepen your understanding of networking concepts.