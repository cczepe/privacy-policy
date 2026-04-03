# Datenschutzerklärung

**Gültig ab:** 2026-04-01

---

## Welche Daten werden erfasst

A-Eye erhebt, speichert und überträgt **keine** personenbezogenen Daten an eigene Server.

Wenn du auf „Analysieren" tippst:
- Das aufgenommene Foto wird direkt an die **Anthropic API** zur Analyse gesendet.
- Das Foto wird von A-Eye nach der Sitzung nicht gespeichert.
- Anthropic verarbeitet das Bild gemäß ihrer eigenen [Datenschutzrichtlinie](https://www.anthropic.com/privacy).

Bilder werden ausschließlich für die Dauer des KI-Analyse-API-Calls verarbeitet. Nach Abschluss der Analyse werden sie weder vom Entwickler noch von der App dauerhaft gespeichert.

---

## Speicherung des API-Schlüssels

Dein Anthropic API-Schlüssel wird lokal auf deinem Gerät mit Android DataStore gespeichert. Er verlässt das Gerät ausschließlich im `x-api-key`-Header von Anfragen an `api.anthropic.com`.

---

## Verwendete Berechtigungen

| Berechtigung | Zweck |
|---|---|
| `CAMERA` | Fotos für die Analyse aufnehmen |
| `INTERNET` | Bilder an die Anthropic API senden |
| `WRITE_EXTERNAL_STORAGE` | Analysierte Bilder in der Galerie speichern (Android ≤ 9) |

---

## Deine Rechte (DSGVO)

Du hast jederzeit das Recht auf Auskunft, Berichtigung und Löschung deiner personenbezogenen Daten. Da A-Eye keine Nutzerdaten dauerhaft speichert, gibt es schlicht keine Daten zu löschen. Für Anfragen stehen wir dennoch gerne zur Verfügung.

---

## Kontakt

Bei Fragen zum Datenschutz oder zur Ausübung deiner DSGVO-Rechte wende dich an:

**E-Mail:** developer@czepe.at

Die jeweils aktuelle Version dieser Datenschutzerklärung ist veröffentlicht unter:
[https://cczepe.github.io/privacy-policy/a-eye/](https://cczepe.github.io/privacy-policy/a-eye/)
