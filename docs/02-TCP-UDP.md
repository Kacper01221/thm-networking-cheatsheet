# TCP vs UDP Cheat Sheet

---

## TCP 3-Way Handshake
1. **SYN**: The client sends a SYN (synchronize) packet to the server.
2. **SYN-ACK**: The server responds with a SYN-ACK (synchronize-acknowledge) packet.
3. **ACK**: The client sends back an ACK (acknowledge) packet to the server.

### Polish:
1. **SYN**: Klient wysyła pakiet SYN (synchronizuj) do serwera.
2. **SYN-ACK**: Serwer odpowiada pakietem SYN-ACK (synchronizuj-potwierdź).
3. **ACK**: Klient wysyła z powrotem pakiet ACK (potwierdź) do serwera.

---

## TCP vs UDP Comparison
| Feature                     | TCP                          | UDP                          |
|-----------------------------|------------------------------|------------------------------|
| Connection-oriented          | Yes                          | No                           |
| Reliable delivery            | Yes                          | No                           |
| Order of packets             | Yes                          | No                           |
| Speed                        | Slower                       | Faster                       |
| Suitable for                | File transfer, web pages     | Streaming, gaming            |

### Polish:
| Cechy                        | TCP                          | UDP                          |
|-----------------------------|------------------------------|------------------------------|
| Ukierunkowane połączenie    | Tak                          | Nie                          |
| Niezawodne dostarczanie      | Tak                          | Nie                          |
| Kolejność pakietów          | Tak                          | Nie                          |
| Prędkość                    | Wolniejszy                   | Szybszy                      |
| Odpowiedni do              | Transfer plików, strony www  | Streaming, gry               |

---

## Common Protocols
- **TCP**: HTTP, FTP, SMTP
- **UDP**: DNS, DHCP

### Polish:
- **TCP**: HTTP, FTP, SMTP
- **UDP**: DNS, DHCP

---

## Memory Tricks
- **TCP**: Think of the 3 steps: SYN, SYN-ACK, ACK as a handshake.
- **UDP**: "Best Effort" delivery, think of tossing a ball vs. handing it directly.

### Polish:
- **TCP**: Pomyśl o 3 krokach: SYN, SYN-ACK, ACK jako uścisku dłoni.
- **UDP**: Dostawa "na najlepszym poziomie", pomyśl o rzucaniu piłki a nie o podawaniu jej.

---

## Practice Questions
1. What is the main difference between TCP and UDP?
2. Describe the TCP 3-way handshake.

### Polish:
1. Jaka jest główna różnica między TCP a UDP?
2. Opisz 3-etapowy uścisk dłoni TCP.

---

## Interactive Commands
- **TCP**: Trace a TCP connection with `traceroute`.
- **UDP**: Check UDP services with `netstat -u`.

### Polish:
- **TCP**: Śledź połączenie TCP za pomocą `traceroute`.
- **UDP**: Sprawdź usługi UDP za pomocą `netstat -u`.