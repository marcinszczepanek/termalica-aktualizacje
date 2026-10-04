# termalica-aktualizacje

Publiczne pliki aktualizacji dla ramek e-ink Termalica (ESP32-S3).

- `manifest.json` — numer i nazwa najnowszej wersji, adres pliku, SHA-256 i podpis ECDSA P-256.
- `firmware-NNN.bin` — skompilowane oprogramowanie.

Ramki pobierają manifest raz na dobę i instalują tylko pliki z poprawnym podpisem.
Kod źródłowy jest w prywatnym repozytorium.
