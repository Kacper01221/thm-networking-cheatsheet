# OSI and TCP/IP Models

## OSI Model

### Layers
1. **Physical Layer**: Transmits raw bitstreams over a physical medium.
2. **Data Link Layer**: Provides node-to-node data transfer and error detection.
3. **Network Layer**: Handles routing of data packets across networks.
4. **Transport Layer**: Ensures reliable transmission of data segments.
5. **Session Layer**: Manages sessions between applications.
6. **Presentation Layer**: Translates data between a format usable by the application and the network format.
7. **Application Layer**: Provides network services to end-user applications.

### Comparison Table (English)
| OSI Layer        | Description                                | Protocols                  |
| ---------------- | ------------------------------------------ | -------------------------- |
| Physical         | Bit transmission over physical medium     | Ethernet, USB, DSL        |
| Data Link        | Data transfer between nodes                | Ethernet, PPP, HDLC       |
| Network          | Routing of packets                         | IP, ICMP, ARP             |
| Transport        | Reliable data transfer                     | TCP, UDP                  |
| Session          | Managing sessions                          | NetBIOS, RPC              |
| Presentation     | Data translation and encryption            | SSL, TLS                  |
| Application      | End-user services                          | HTTP, FTP, SMTP           |

### Comparison Table (Polish)
| Warstwa OSI      | Opis                                       | Protokół                  |
| ---------------- | ------------------------------------------ | -------------------------- |
| Fizyczna         | Transmisja bitów przez medium fizyczne   | Ethernet, USB, DSL        |
| Łącza Danych     | Transfer danych pomiędzy węzłami          | Ethernet, PPP, HDLC       |
| Sieciowa         | Routing pakietów                          | IP, ICMP, ARP             |
| Transportowa     | Niezawodny transfer danych                 | TCP, UDP                  |
| Sesyjna          | Zarządzanie sesjami                        | NetBIOS, RPC              |
| Prezentacji      | Tłumaczenie i szyfrowanie danych          | SSL, TLS                  |
| Aplikacji        | Usługi dla użytkowników końcowych         | HTTP, FTP, SMTP           |

## TCP/IP Model

### Layers
1. **Network Interface**: Combines the physical and data link layers.
2. **Internet**: Corresponds to the OSI network layer.
3. **Transport**: Similar to the OSI transport layer.
4. **Application**: Combines the OSI session, presentation, and application layers.

### Comparison Table (English)
| TCP/IP Layer     | Description                                | Protocols                  |
| ---------------- | ------------------------------------------ | -------------------------- |
| Network Interface | Transmits data over physical medium       | Ethernet, Wi-Fi           |
| Internet         | Routing between devices                    | IP, ICMP                  |
| Transport        | Communication services between applications| TCP, UDP                  |
| Application      | End-user services                          | HTTP, FTP, SMTP           |

### Comparison Table (Polish)
| Warstwa TCP/IP   | Opis                                       | Protokół                  |
| ---------------- | ------------------------------------------ | -------------------------- |
| Interfejs Sieciowy| Transmisja danych przez medium fizyczne   | Ethernet, Wi-Fi           |
| Sieć            | Routing pomiędzy urządzeniami             | IP, ICMP                  |
| Transport        | Usługi komunikacyjne pomiędzy aplikacjami | TCP, UDP                  |
| Aplikacja        | Usługi dla użytkowników końcowych         | HTTP, FTP, SMTP           |

## Memory Tricks
- **OSI**: "Please Do Not Throw Sausage Pizza Away" to remember the layer sequence.
- **TCP/IP**: "I Always Find Time" can help recall the layers.

## Practice Questions
1. What is the function of the Transport layer in the OSI model?
2. How do the OSI and TCP/IP models differ in terms of layers?
3. What are some protocols used in the Application layer of both models?

### Polish Questions
1. Jaka jest funkcja warstwy Transport w modelu OSI?
2. Jak różnią się modele OSI i TCP/IP pod względem warstw?
3. Jakie protokoły są używane w warstwie Aplikacji obu modeli?