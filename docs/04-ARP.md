# ARP Basics
Address Resolution Protocol (ARP) is a communication protocol used for discovering mac addresses and mapping them to internet protocol (IP) addresses. It operates at the link layer.

## ARP Podstawy
Protokół ARP (Address Resolution Protocol) jest protokołem komunikacyjnym używanym do odkrywania adresów MAC i mapowania ich na adresy IP. Działa na warstwie łącza.

# 4-Step ARP Process
1. ARP Request: A host sends out an ARP request packet to discover the MAC address of a host with a specific IP address.
2. ARP Reply: The identified host responds with an ARP reply containing its MAC address.
3. Cache Update: The initiating host updates its ARP cache with the new information.
4. Data Transmission: Data is then transmitted using the discovered MAC address.

## Proces ARP w 4 Krokach
1. Żądanie ARP: Host wysyła pakiet żądania ARP w celu odkrycia adresu MAC hosta o określonym adresie IP.
2. Odpowiedź ARP: Zidentyfikowany host odpowiada odpowiedzią ARP zawierającą swój adres MAC.
3. Aktualizacja pamięci podręcznej: Inicjujący host aktualizuje swoją pamięć podręczną ARP nowymi informacjami.
4. Przesyłanie danych: Dane są następnie przesyłane przy użyciu odkrytego adresu MAC.

# ARP Spoofing Attacks
ARP spoofing is a technique used by attackers to send false ARP messages onto a local area network, resulting in the linking of their MAC address to the IP address of another host.

## Ataki Fałszowania ARP
Fałszowanie ARP to technika używana przez atakujących do wysyłania fałszywych komunikatów ARP do lokalnej sieci, co skutkuje powiązaniem ich adresu MAC z adresem IP innego hosta.

# Detection and Prevention Methods
- Use static ARP entries for critical hosts.
- Employ ARP monitoring tools to detect suspicious activities.
- Implement port security on switches.

## Metody Wykrywania i Zapobiegania
- Użyj statycznych wpisów ARP dla krytycznych hostów.
- Korzystaj z narzędzi monitorujących ARP w celu wykrywania podejrzanych działań.
- Wdroż zabezpieczenia portów na przełącznikach.

# Practice Questions
1. What is the purpose of ARP?
2. Describe the ARP process.
3. How can ARP spoofing be prevented?

## Pytania Praktyczne
1. Jaki jest cel ARP?
2. Opisz proces ARP.
3. Jak można zapobiec fałszowaniu ARP?

# Interactive Commands
To display the ARP table:
```
arp -a
```

## Polecenia Interaktywne
Aby wyświetlić tabelę ARP:
```
arp -a
```
