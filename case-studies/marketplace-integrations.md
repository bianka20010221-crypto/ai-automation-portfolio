# Marketplace és üzleti integrációk

[← Vissza a projektmenühöz](../README.md#project-menu)

**English summary:** Practical commerce and business integrations covering product imports, invoicing, loyalty, communication and OAuth-based services, with idempotency, validation and traceable failure handling.

## Gyakorlati területek

- UNAS termékadat-importok, szinkronizáció és validáció;
- WooCommerce és WordPress webshopfolyamatok;
- PassKit-alapú, többszintű hűségprogram;
- MailerLite szegmentáció és automatizált kommunikáció;
- Billingo és Számlázz.hu kapcsolati minták;
- Gmail, Google Calendar és Microsoft Graph OAuth-integráció;
- REST/JSON, webhook, JWT/RS256 és API-kulcs alapú hitelesítés.

## Integrációs alapelvek

1. A hitelesítő adatok nem kerülnek a repositoryba.
2. Az OAuth-state és a callback bemenetek validálva vannak.
3. Az ismételt webhook nem okozhat dupla műveletet.
4. A külső hiba naplózott és visszakövethető.
5. Az adatgazda, a jogosultság és az üzleti felelős megnevezése a technikai fejlesztés része.
