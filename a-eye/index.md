# Privacy Policy

**Effective date:** 2024-01-01

## What data is collected

A-Eye does **not** collect, store, or transmit any personal data to its own servers.

Wenn du auf „Analysieren" tippst:
- Das aufgenommene Foto wird direkt an die **Anthropic API** zur Analyse gesendet
- Das Foto wird von A-Eye nach der Sitzung nicht gespeichert
- Anthropic verarbeitet das Bild gemäß ihrer eigenen [Datenschutzrichtlinie](https://www.anthropic.com/privacy)

## API-Schlüssel-Speicherung

Dein Anthropic API-Schlüssel wird lokal auf deinem Gerät mit Android DataStore gespeichert. Er wird ausschließlich im `x-api-key`-Header von Anfragen an `api.anthropic.com` übertragen.

## Verwendete Berechtigungen

| Berechtigung | Grund |
|---|---|
| `CAMERA` | Fotos für die Analyse aufnehmen |
| `INTERNET` | Bilder an die Anthropic API senden |
| `READ_MEDIA_IMAGES` / `WRITE_EXTERNAL_STORAGE` | Analysierte Bilder in der Galerie speichern |
