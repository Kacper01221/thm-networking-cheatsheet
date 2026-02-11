# DNS Hierarchy

## Hierarchia DNS

DNS (Domain Name System) jest hierarchicznym systemem nazw, który przekształca nazwy domenowe na adresy IP.

1. **Root Domain** (Domena główna)
   - Najwyższy poziom w hierarchii DNS.
   - Zazwyczaj wizualizowany jako kropka (.)

2. **Top-Level Domains (TLD)** (Domeny najwyższego poziomu)
   - Jak .com, .org, .net

3. **Second-Level Domains (SLD)** (Domeny drugiego poziomu)
   - Nazwy edycji domen, np. google w google.com

4. **Subdomains** (Subdomeny)
   - Podstrony, np. mail.google.com

---

## DNS Query Process

## Proces zapytania DNS

1. **User Types DNS Query** (Użytkownik wpisuje zapytanie DNS)
2. **Local DNS Resolver** (Lokalny resolver DNS)
   - Sprawdza pamięć podręczną.
3. **Root Name Server** (Serwer główny)
   - Kieruje zapytanie do odpowiedniego TLD.
4. **TLD Name Server** (Serwer TLD)
   - Kieruje zapytanie do serwera DNS SLD.
5. **SLD Name Server** (Serwer SLD)
   - Zwraca adres IP do lokalnego resolvera.
6. **Local DNS Resolver Returns IP Address** (Lokalny resolver zwraca adres IP)

---

## DNS Record Types

### Typy rekordów DNS

1. **A Record** (Rekord A)
   - Zawiera adres IPv4.

2. **AAAA Record** (Rekord AAAA)
   - Zawiera adres IPv6.

3. **CNAME Record** (Rekord CNAME)
   - Alias dla innej nazwy domenowej.

4. **MX Record** (Rekord MX)
   - Kieruje wiadomości e-mail do serwera poczty.

5. **NS Record** (Rekord NS)
   - Określa serwer nazw z autorytetem dla danej strefy.

6. **SOA Record** (Rekord SOA)
   - Informacje o strefie.

7. **TXT Record** (Rekord TXT)
   - Przechowuje tekstowe dane.

8. **PTR Record** (Rekord PTR)
   - Używany do odwrotnego DNS lookup.

---

## DNS Caching

### Pamięć podręczna DNS

DNS caching polega na przechowywaniu wyników wcześniejszych zapytań, co przyspiesza dostęp do często odwiedzanych domen.

### Time-To-Live (TTL) Explanation

TTL jest czasem, przez który rekord DNS może być przechowywany w pamięci podręcznej zanim zostanie odświeżony.

---

## Practice Questions

### Pytania do ćwiczeń

1. Jakie są różnice między rekordami A a AAAA?
2. Co to jest TTL i dlaczego jest ważny?
3. Jak działa proces zapytania DNS?
4. Jakie typy rekordów DNS mogą być używane w e-mailu?

---

## Interactive Commands

### Interaktywne polecenia

- **nslookup [domain]**: Używane do zapytań o rekordy DNS.
- **dig [domain]**: Rozbudowane zapytanie DNS dla różnych rekordów.
- **ping [domain]**: Sprawdza dostępność adresu.

# References

1. [What is DNS?](https://www.cloudflare.com/learning/dns/what-is-dns/)
2. [DNS Basics](https://www.cloudflare.com/learning/dns/dns-basics/)
