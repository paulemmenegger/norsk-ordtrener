# Norsk Ordtrener

Vokabel-Übungs-App für Norwegisch (Bokmål – Deutsch), Wortschatz A1 bis B1, 2251 Einträge in 35 Themen.

Ein Projekt von **SeetalIT** · [seetalit.ch](https://seetalit.ch) · Paul Emmenegger, Hochdorf

- `index.html` – die App (eine Datei, kein Build nötig)
- `books/` – Wortlisten, eine JSON-Datei pro Niveau (`books/index.json` listet sie)
- `fonts/` – Schriften für Logo (Nunito Sans) und Titel (Metamorphous), beide unter der SIL Open Font License (Texte liegen bei)
- Schalter (App an/aus, freigeschaltete Kapitel) und Login der Lehrperson laufen über Supabase.

Neues Niveau: JSON nach `books/` legen und in `books/index.json` unter `books` eintragen (unter `upcoming` erscheint es als Reiter «folgt bald»).

---

© 2026 SeetalIT. Alle Rechte vorbehalten.
