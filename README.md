# SR-Doku Basic

*Basic* = schlank, für die MDR unkritisch. Die erweiterte Variante *SR-Doku Pro* (Prototyp, MDR-Prüfung ausstehend) liegt im Repo SR-Doku.

Software zur strukturierten Dokumentation der Schockraumversorgung durch medizinisches Fachpersonal (Version 0.2.0, Stand 08.11.2026).

**Vorabversion.** Die Zweckbestimmung befindet sich in rechtlicher Prüfung.

**Zweckbestimmung:** Strukturierte Dokumentation der Schockraumversorgung und Anzeige klinikeigener, für alle Patienten gleicher Listen und Dokumente. Die Software wertet keine Patientendaten aus, berechnet keine Scores, sortiert oder hebt nichts nach Patientendaten hervor, löst keine Warnungen oder Alarme aus und gibt keine diagnostischen oder therapeutischen Empfehlungen.

SR-Doku Basic – Dokumentationssoftware, nicht als Medizinprodukt bestimmt. Version 0.2.0, Stand 08.11.2026.

## Inhalt dieses Repositorys

| Datei | Zweck |
|---|---|
| `index.html` | Sperrseite. Die App liegt darin nur verschlüsselt vor (AES-256-GCM, PBKDF2-SHA-256 mit 310 000 Iterationen) und wird erst nach Eingabe des Passworts im Browser entschlüsselt. |
| `site.webmanifest`, `*.png` | Name und Icon für „Zum Home-Bildschirm“ |
| `THIRD_PARTY_LICENSES.md` | Lizenzen der eingebundenen Bibliotheken |

Das Passwort steht nicht im Repository.

## GitHub Pages

Settings → Pages → Source „Deploy from a branch“, Branch `main`, Ordner `/ (root)`.

## Datenhaltung

- Lokales Konto (Registrierung/Anmeldung) nur auf dem Gerät; der gespeicherte Fall ist je Konto verschlüsselt (AES-256-GCM). Kein Server.
- Alle Falldaten bleiben lokal im Browser des Geräts.
- Kein Server, keine Telemetrie, keine Anfragen an Dritte.
- Übergabe an ein anderes Gerät nur per verschlüsseltem QR-Code mit mündlich weitergegebenem 8-stelligem Code.

© 2026 Lars Mühlen
