![RisikoDetektiv](cover.png)


# RisikoDetektiv Telegram Kanal

> [!IMPORTANT]
> **Dieses Projekt wurde im September 2026 eingestellt.** Der Kanal veröffentlicht keine neuen Beiträge mehr, und dieses Repository ist archiviert (nur noch lesbar).
>
> Aktuelle Informationen zu Ransomware-Angriffen in Deutschland bieten zum Beispiel [ransomware.live](https://www.ransomware.live/country/DEU) und das [BSI](https://www.bsi.bund.de).

RisikoDetektiv war ein Telegram-Kanal ([@RisikoDetektiv](https://t.me/RisikoDetektiv)), der Cybersecurity-Bedrohungen verfolgte. Er meldete automatisch, wenn Organisationen aus Deutschland auf den Leak-Seiten von Ransomware-Gruppen genannt wurden. Grundlage waren Metadaten von Open-Source-Plattformen.

## Warum eingestellt?

- Die ursprünglich genutzte Datenquelle steht in dieser Form nicht mehr zur Verfügung; [ransomwatch](https://github.com/joshhighet/ransomwatch) ist seit März 2026 archiviert.
- Spezialisierte Tracker wie [ransomware.live](https://www.ransomware.live) decken das Thema inzwischen umfassend und mit eigenen Schnittstellen ab.

## Status des Codes

`main.py` ist nur noch aus historischen Gründen enthalten. Das Skript ist in dieser Form nicht lauffähig: Die abgefragte Datenquelle existiert nicht mehr, und das Skript enthält bekannte Fehler. Bitte nicht produktiv einsetzen.

⚠️ **Haftungsausschluss:**
Die Beiträge des Kanals gaben Behauptungen von Ransomware-Gruppen auf deren Leak-Seiten wieder und stellten keine Bestätigung eines Angriffs dar. Alle Informationen stammten aus öffentlichen Quellen; für ihre Richtigkeit wird keine Gewähr übernommen.

🔒 **Datenschutz:**
Der Kanal verwendete ausschließlich Metadaten aus öffentlichen Quellen, zum Beispiel den Namen der Organisation, das Datum und die Tätergruppe.

## Credits

1. Julien Mousqueton – [ransomware.live](https://www.ransomware.live)
2. Josh Highet – [ransomwatch](https://github.com/joshhighet/ransomwatch) (seit März 2026 archiviert)
3. Open-Source-Nachrichtenseiten

## Lizenz

RisikoDetektiv ist unter der [Unlicense](LICENSE.md) veröffentlicht (Public Domain).
