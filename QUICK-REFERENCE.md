# Quick Reference

## Protocols by Port
| Protocol      | Port    |
|---------------|---------|
| HTTP          | 80      |
| HTTPS         | 443     |
| FTP           | 21      |
| SFTP          | 22      |
| SSH           | 22      |
| DNS           | 53      |
| DHCP          | 67/68   |
| TFTP          | 69      |
| SNMP          | 161     |
| LDAP          | 389     |
| ...           | ...     |

## Protocols by Layer
| Layer         | Protocols                       |
|---------------|--------------------------------|
| Application   | HTTP, FTP, DNS, SMTP           |
| Transport     | TCP, UDP                       |
| Internet      | IP, ICMP                       |
| Link          | Ethernet, WiFi                 |

## HTTP Status Codes
| Code | Description                          |
|------|--------------------------------------|
| 200  | OK                                   |
| 404  | Not Found                            |
| 500  | Internal Server Error                |
| ...  | ...                                  |

## DNS Record Types
| Type  | Description                      |
|-------|----------------------------------|
| A     | Address record                   |
| AAAA  | IPv6 address record              |
| CNAME | Canonical name record            |
| MX    | Mail exchange record             |
| PTR   | Pointer record                   |
| ...   | ...                              |

## TCP Handshake
1. SYN - Synchronize
2. SYN-ACK - Synchronize-Acknowledge
3. ACK - Acknowledge

## DHCP DORA Process
1. Discovery
2. Offer
3. Request
4. Acknowledgment

## OSI Layer Cheatsheet
| Layer       | Function                               |
|-------------|---------------------------------------|
| 7: Application | End-user software                    |
| 6: Presentation | Data format translation              |
| 5: Session      | Establishes sessions                 |
| 4: Transport    | End-to-end communication             |
| 3: Network      | Routing of data packets             |
| 2: Data Link    | Node to node data transfer          |
| 1: Physical     | Physical medium and signals         |

## IPv4 Address Classes
| Class | Range                |
|-------|----------------------|
| A     | 1.0.0.0 to 126.0.0.0  |
| B     | 128.0.0.0 to 191.255.0.0 |
| C     | 192.0.0.0 to 223.255.255.0 |
| ...   | ...                  |

## Private IP Ranges
| Class | Range                |
|-------|----------------------|
| A     | 10.0.0.0 to 10.255.255.255 |
| B     | 172.16.0.0 to 172.31.255.255 |
| C     | 192.168.0.0 to 192.168.255.255 |

## Subnet Mask to CIDR Conversion
| Subnet Mask       | CIDR |
|------------------|------|
| 255.255.255.0    | /24  |
| 255.255.0.0      | /16  |
| 255.0.0.0        | /8   |
| ...              | ...  |

## Common Nmap Commands
- `nmap -sP 192.168.1.0/24` - Ping scan
- `nmap -sT -p 80,443 example.com` - TCP connect scan
- ...

## Tcpdump Filters
- `tcpdump -i eth0 port 80` - Capture HTTP traffic
- `tcpdump host 192.168.1.1` - Capture traffic to/from a host
- ...

## ICMP Message Types
| Type | Description                   |
|------|-------------------------------|
| 0    | Echo Reply                    |
| 3    | Destination Unreachable       |
| 8    | Echo Request                  |
| ...  | ...                           |

## Memory Tricks
- Mnemonic for OSI layers: "All People Seem To Need Data Processing"

## Emergency Commands
- `shutdown -h now` - Shutdown immediately
- `reboot` - Reboot the machine

## Study Priorities
1. Understand the basics
2. Focus on hands-on practice
3. Review protocols and their uses
4. Practice networking scenarios and troubleshooting

*Note: The tables above are simplified and meant as quick reference guides. For detailed understanding, consult comprehensive networking materials or texts.*
