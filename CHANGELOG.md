# Changelog - PRAMGEN

## v1.10.2 (2026-03-18)
- **Fix actualizare automata**: inlocuit subprocess.Popen cu os.startfile pentru lansarea instalatorului; elevarea UAC functioneaza corect si update-ul nu mai esua silentios

## v1.10.1 (2026-03-17)
- **Fix OneDrive**: eliminat scope rezervat offline_access din MSAL (cauza crash silentios inainte de a porni fluxul device code)
- **Persistenta token OneDrive**: trecut la SerializableTokenCache; token salvat pe disc si refresh silentios functional dupa repornire
- **Mesaje erori OneDrive**: erorile de autentificare sunt afisate ca dialog, nu in eticheta de progres minuscula
- **Seed DB (mod developer)**: dialog de generare date false (ingineri, dispozitive, companie, certificate)

## v1.10.0 (2026-03-13)
- **Fix Cloud Sync toate providerele**: Google Drive, OneDrive si Nextcloud ridica RuntimeError cu mesaje utile in loc de esecuri silentioase
- **Fix Google Drive**: refresh token expirat ridica RuntimeError cu instructiuni de reconectare
- **Fix OneDrive/Nextcloud**: upload/download ridica RuntimeError la token expirat sau erori HTTP

## v1.9.1 (2026)
- **Multi-provider Cloud Sync**: Google Drive, OneDrive si Nextcloud pot fi active simultan
- **Integrare Nextcloud**: sincronizare WebDAV cu parola de aplicatie

## v1.8.3 (2026)
- Fix captcha PIN si fix inchidere aplicatie din fereastra PIN

## v1.8.2 (2026)
- Fix integritate manifest; actualizare automata din banner; 168 teste automate

## v1.8 (2026)
- Cloud Sync Google Drive si OneDrive cu criptare AES-256; licenta cloud pe 10 dispozitive

## v1.7 (2025)
- Protectie PIN, logo filigran PDF, criptare PDF 128-bit RC4, calendar integrat

## v1.6 (2024)
- Lansare initiala: PDF, SQLite, actualizari automate, verificare integritate
