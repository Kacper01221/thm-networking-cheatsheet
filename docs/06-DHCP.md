# DHCP Explanation

DHCP (Dynamic Host Configuration Protocol) is a network management protocol used on IP networks to automatically assign IP addresses and other network configuration parameters to devices, allowing them to communicate on the network.

## DORA Process
The DORA process consists of four main steps:
1. **Discover**: The client sends a DHCPDISCOVER message to the broadcast address to find available DHCP servers.
2. **Offer**: DHCP servers receive the DISCOVER message and respond with a DHCPOFFER message that includes an available IP address and other configuration details.
3. **Request**: The client responds to the chosen DHCP server with a DHCPREQUEST message, indicating its acceptance of the offer.
4. **Acknowledge**: The DHCP server sends a DHCPACK message to the client, confirming the assigned IP address and configuration settings.

## DHCP Lease
A DHCP lease is the amount of time a client is allowed to use an assigned IP address. The lease duration can vary, and once it expires, the client must renew it or will be assigned a new IP address.

## DHCP Starvation Attacks
DHCP starvation is a type of denial-of-service attack where an attacker floods the DHCP server with requests, consuming all available IP addresses. This leads to other clients being unable to obtain an IP address.

## Practice Questions
1. What is the primary function of DHCP?
2. Describe the DORA process in DHCP.
3. What happens when a DHCP lease expires?
4. How can DHCP starvation attacks be mitigated?

## Interactive Commands
- To view DHCP leases on a Windows server: `Get-DhcpServerv4Lease`
- To release a DHCP lease on a Windows client: `ipconfig /release`
- To renew a DHCP lease on a Windows client: `ipconfig /renew`

---

# Wyjaśnienie DHCP

DHCP (Protokół dynamicznego przypisywania adresów) to protokół zarządzania siecią używany w sieciach IP do automatycznego przypisywania adresów IP oraz innych parametrów konfiguracyjnych sieci urządzeniom, co pozwala im na komunikację w sieci.

## Proces DORA
Proces DORA składa się z czterech głównych kroków:
1. **Odkrywanie**: Klient wysyła wiadomość DHCPDISCOVER na adres rozgłoszeniowy, aby znaleźć dostępne serwery DHCP.
2. **Oferta**: Serwery DHCP otrzymują wiadomość DISCOVER i odpowiadają wiadomością DHCPOFFER, która zawiera dostępny adres IP i inne szczegóły konfiguracyjne.
3. **Żądanie**: Klient odpowiada na wybranego serwera DHCP wiadomością DHCPREQUEST, wskazując na akceptację oferty.
4. **Potwierdzenie**: Serwer DHCP wysyła wiadomość DHCPACK do klienta, potwierdzając przyznany adres IP i ustawienia konfiguracyjne.

## Czas dzierżawy DHCP
Czas dzierżawy DHCP to czas, w którym klient może korzystać z przypisanego adresu IP. Czas dzierżawy może się różnić, a po jego wygaśnięciu klient musi go odnowić lub otrzyma nowy adres IP.

## Ataki głodzenia DHCP
Głodzenie DHCP to rodzaj ataku typu denial-of-service, w którym napastnik zalewa serwer DHCP żądaniami, konsumując wszystkie dostępne adresy IP. To prowadzi do sytuacji, w której inne urządzenia nie mogą uzyskać adresu IP.

## Pytania do ćwiczeń
1. Jaka jest podstawowa funkcja DHCP?
2. Opisz proces DORA w DHCP.
3. Co się dzieje, gdy czas dzierżawy DHCP wygaśnie?
4. Jak można złagodzić ataki głodzenia DHCP?

## Interaktywne polecenia
- Aby wyświetlić dzierżawy DHCP na serwerze Windows: `Get-DhcpServerv4Lease`
- Aby zwolnić dzierżawę DHCP na kliencie Windows: `ipconfig /release`
- Aby odnowić dzierżawę DHCP na kliencie Windows: `ipconfig /renew` 
