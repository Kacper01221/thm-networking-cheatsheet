# ICMP (Internet Control Message Protocol)

## Typy komunikatów ICMP
- **Echo Request** (typ 8) – Proszono o odpowiedź (used by ping).
- **Echo Reply** (typ 0) – Odpowiedź na echo request (ping).
- **Destination Unreachable** (typ 3) – Nie można osiągnąć celu.
- **Time Exceeded** (typ 11) – Przekroczony czas oczekiwania.
- **Redirect** (typ 5) – Przekierowanie do innej trasy.

## Wyjaśnienia ping i traceroute
### Ping
Ping jest narzędziem, które wysyła echo request do określonego hosta, aby sprawdzić dostępność i czas odpowiedzi. 

**Przykład użycia:**  
`ping example.com`

### Traceroute
Traceroute wyznacza trasę, jaką pakiety danych przyjmują, aby dotrzeć do określonego celu, pokazując wiele przystanków (routerów) na drodze. 

**Przykład użycia:**  
`traceroute example.com`

## Przykłady zastosowań
1. Diagnostyka ręczna problemów z dostępnością sieci.
2. Analiza trasowania i opóźnień w sieci.
3. Wykrywanie problemów z routingiem w sieciach rozległych.

## Pytania do praktyki
1. Co oznacza komunikat ICMP "Destination Unreachable"?
2. Jakie są typowe przyczyny wysokich opóźnień w odpowiedziach ping?

## Interaktywne komendy
- `ping -c 4 example.com` – Wysyła cztery pakiety echo request.  
- `traceroute example.com` – Sprawdza trasę do hosta.

## ICMP (Internet Control Message Protocol)

## ICMP message types
- **Echo Request** (type 8) - A request for a reply (used by ping).
- **Echo Reply** (type 0) - A reply to an echo request (ping).
- **Destination Unreachable** (type 3) - Cannot reach the destination.
- **Time Exceeded** (type 11) - Time limit exceeded.
- **Redirect** (type 5) - Redirected to another route.

## Explanations of ping and traceroute
### Ping
Ping is a tool that sends an echo request to a specified host to check availability and response time.

**Example usage:**
`ping example.com`

### Traceroute
Traceroute determines the path that data packets take to reach a specific destination, showing multiple stops (routers) along the way.

**Example usage:**
`traceroute example.com`

## Use Cases
1. Manual diagnostics of network availability issues.
2. Analysis of routing and delays in the network.
3. Detection of routing problems in wide area networks.

## Practice Questions
1. What does the ICMP message 'Destination Unreachable' mean?
2. What are common causes of high latency in ping responses?

## Interactive Commands
- `ping -c 4 example.com` - Sends four echo request packets.
- `traceroute example.com` - Checks the route to a host.