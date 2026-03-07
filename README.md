# PRAMGEN — Generator Raport Rezistenta Dispersie Priza de Pamant

**PRAMGEN** este o aplicatie desktop pentru generarea rapoartelor de incercare a rezistentei de dispersie a prizelor de pamant, conform normativelor romanesti **I7-2011**, **PE 116/94** si **1RE-Ip 30/2004**.

---

## Functionalitati principale

- Generare rapoarte PDF profesionale cu antet companie, semnaturi si stampila
- Filigran cu logoul companiei la 10% opacitate in fiecare pagina PDF
- Criptare PDF (128-bit RC4): tiparire permisa, copiere/editare blocata
- Istoric certificate cu cautare, reimprimare si stergere
- Autocompletare campuri din istoricul anterior
- Calendar integrat pentru selectarea datelor
- Coeficient de corectie configurabil pentru calculul R calculata

## Securitate

- Protectie optionala cu PIN (SHA-256, captcha dupa 2 incercari, blocare dupa 5)
- Verificare integritate fisiere la pornire
- Instanta unica (mutex Windows)

## Licentiere

| Versiune | Limitare |
|---|---|
| **Gratuita** | 1 raport PDF / zi calendaristic |
| **Comerciala** | Generare nelimitata + Cloud Sync |

Licenta comerciala este legata de hardware-ul masinii sau de contul cloud al utilizatorului.

## Cloud Sync (v1.8+, licenta comerciala)

- Sincronizare baza de date cu **Google Drive** sau **OneDrive**
- Criptare AES-256 a bazei de date inainte de incarcare
- Licenta cloud valabila pe pana la **10 dispozitive** conectate la acelasi cont
- Sincronizare automata la pornire si dupa fiecare certificat generat

## Instalare

Descarca cel mai recent fisier `PRAMGEN_Setup_X.X.exe` din [Releases](../../releases) si ruleaza-l ca administrator.

**Cerinte sistem:** Windows 10/11 (64-bit)

## Actualizari

La fiecare pornire, aplicatia verifica automat versiunile noi pe GitHub si afiseaza un banner de notificare.

## Contact

- **Producator:** Cristian Casapu
- **Email:** contact@cristiancasapu.ro
- **Licente comerciale:** contact@cristiancasapu.ro
