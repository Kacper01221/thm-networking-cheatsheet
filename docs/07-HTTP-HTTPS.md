# HTTP and HTTPS Overview

## HTTP Methods
- **GET**: Otrzymuje dane z serwera.
- **POST**: Wysyła dane do serwera.
- **PUT**: Aktualizuje istniejące dane na serwerze.
- **DELETE**: Usuwa dane z serwera.

## Status Codes
- **1xx**: Informacyjne
- **2xx**: Sukces
    - 200 OK: Żądanie powiodło się.
- **3xx**: Przekierowania
- **4xx**: Błędy klienta
    - 404 Not Found: Nie znaleziono.
- **5xx**: Błędy serwera

## HTTP Headers
- `Content-Type`: Określa typ mediów.
- `User-Agent`: Informacje o użytkowniku żądającym.
- `Authorization`: Autoryzacja żądania.

## HTTPS/TLS Explanation
HTTPS (Hypertext Transfer Protocol Secure) zabezpiecza dane w sieci przy użyciu protokołu TLS (Transport Layer Security).

## TLS Handshake
Opis procesu nawiązywania bezpiecznego połączenia TLS.

## HTTP vs HTTPS Comparison
- HTTP: Niezabezpieczone połączenie
- HTTPS: Zabezpieczone połączenie z szyfrowaniem.

## Practice Questions
- Jakie są różnice między HTTP a HTTPS?
- Jakie metody HTTP są najczęściej używane?

## Interactive Commands
- **curl -X GET [URL]**: Przykładowe zapytanie GET.
- **curl -X POST -d 'data' [URL]**: Przykładowe zapytanie POST.