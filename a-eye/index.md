# Datenschutzerklärung

**Gültig ab:** 2026-04-01

---

## Welche Daten werden erfasst

A-Eye erhebt, speichert und überträgt **keine** personenbezogenen Daten an eigene Server.

Wenn du auf „Analysieren" tippst:
- Das aufgenommene Foto wird direkt an die **Anthropic API** zur Analyse gesendet.
- Das Foto wird von A-Eye nach der Sitzung nicht gespeichert.
- Anthropic verarbeitet das Bild gemäß ihrer eigenen [Datenschutzrichtlinie](https://www.anthropic.com/privacy).

---

## Speicherung des API-Schlüssels

Dein Anthropic API-Schlüssel wird lokal auf deinem Gerät mit Android DataStore gespeichert. Er verlässt das Gerät ausschließlich im `x-api-key`-Header von Anfragen an `api.anthropic.com`.

---

## Verwendete Berechtigungen

| Berechtigung | Zweck |
|---|---|
| `CAMERA` | Fotos für die Analyse aufnehmen |
| `INTERNET` | Bilder an die Anthropic API senden |
| `READ_MEDIA_IMAGES` / `WRITE_EXTERNAL_STORAGE` | Analysierte Bilder in der Galerie speichern |

---

## Kontakt

Die jeweils aktuelle Version dieser Datenschutzerklärung ist veröffentlicht unter:
[https://cczepe.github.io/privacy-policy/a-eye/](https://cczepe.github.io/privacy-policy/a-eye/)
