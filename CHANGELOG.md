# Changelog — PRAMGEN

## v1.8.3 (2026)
- **Fix captcha PIN**: captcha nu aparea dupa 2 incercari gresite (bug layout pack)
- **Fix inchidere aplicatie**: aplicatia nu putea fi inchisa din fereastra PIN

## v1.8.2 (2026)
- **Fix integritate**: manifest regenerat corect la fiecare build (v1.8/v1.8.1 afisau eroare de coruptie la pornire dupa actualizare)
- **Actualizare automata**: buton "Actualizeaza automat" in bannerul de update — descarca si instaleaza noua versiune fara a parasi aplicatia
- **Suite teste**: 168 teste automate (de la 109), acoperire noua: cloud sync, criptare, constante, comparare versiuni

## v1.8 (2026)
- **Cloud Sync**: sincronizare baza de date cu Google Drive si OneDrive (criptare AES-256)
- **Licenta cloud**: valabila pe pana la 10 dispozitive pe acelasi cont cloud
- **Generator licente**: tab nou "Licenta cloud" pentru generare cheie pe baza email
- **Setari > Cloud Sync**: conectare/deconectare, sincronizare manuala, gestiune dispozitive
- Cloud Sync disponibil exclusiv cu licenta comerciala activa

## v1.7 (2025)
- **PIN protection**: cod PIN optional (SHA-256), captcha dupa 2 incercari, blocare dupa 5
- **Licenta badges**: NICIO LICENTA / LICENTIAT / EXPIRA CURAND / EXPIRAT / MASINA DIFERITA
- **Logo filigran**: logo companie la 10% opacitate in PDF (Pillow)
- **PDF criptare**: 128-bit RC4, tiparire permisa, copiere/editare blocata
- **Calendar**: selectie automata la click pe zi, fara buton OK
- **Ajutor**: link-uri clicabile email/GitHub, rebranduit
- Preset-uri "Instalatie verificata" conform normative romanesti

## v1.6 (2024)
- Lansare initiala publica
- Generator PDF cu ReportLab
- Istoric certificate (SQLite)
- Actualizari automate (GitHub API)
- Verificare integritate fisiere
