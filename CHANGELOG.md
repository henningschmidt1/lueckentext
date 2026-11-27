# Changelog – Kooperativer Lückentext

## Version 1.2 – 27.11.2026

### Geändert
- Kopfzeile kleiner: Rolle und Titel in einer Zeile, kleinere Schrift, weniger Innenabstand.
- Bedienhinweis vom Seitenanfang unter den Text verschoben (über der Versionsangabe), kleiner und grau.

### Getestet
- 27.11.2026: alle Tests laut Testplan Version 1 auf echten Geräten erfolgreich. Version 1 abgeschlossen.

## Version 1.1 – 27.11.2026

### Neu
- Umgekehrte Reihenfolge möglich: erst leere Lücke antippen (dicker Rahmen), dann Wort antippen → Wort wird eingesetzt. Erneutes Antippen der Lücke hebt die Auswahl auf. Reihenfolge Wort → Lücke funktioniert weiter.

### Geändert
- Hinweistext oben: „Wort und Lücke antippen – in beliebiger Reihenfolge.“

## Version 1.0 – 25.11.2026

### Neu
- Eine HTML-Datei ohne externe Bibliotheken; Importtext im markierten Bereich am Anfang des Quelltexts.
- Prüfung des Importtexts beim Laden (Titel, Lösungswort, Text, Füllwörter, genau 8 Lücken, Klammern, Dubletten, Füllwort = Lösungswort, Lösungswort ≥ 4 Buchstaben) mit verständlichen Meldungen.
- Rollen über die Adresse: `?rolle=A` (blau), `?rolle=B` (grün), `?rolle=solo` (grau, Übung). Ohne Rolle: Auswahlseite mit drei Links.
- Verteilung: Lücken abwechselnd A/B; Füllwörter abwechselnd, je Rolle 2. Übung: alle Lösungs- und Füllwörter.
- Bedienung: Wort antippen, dann Lücke antippen; befüllte Lücke antippen gibt das Wort frei; Wort auf befüllte Lücke ersetzt das alte.
- Wortleiste fest am unteren Rand, Wörter gemischt, eingesetzte Wörter ausgegraut.
- Leere Lücken gleich breit, befüllte passen sich an.
- Prüfen: Fehlerzahl, falsche Lücken mit rotem Rand; ohne Fehler Teil des Lösungsworts (A größere Hälfte) mit Aufforderung zum Zusammensetzen; Übung zeigt das ganze Lösungswort.
- „Neu starten“ mit Bestätigung durch zweites Antippen (3 Sekunden).
- Versionsnummer und Datum am Seitenende.
- „Prüfen“ wird aktiv, sobald 4 Wörter eingesetzt sind (Anzahl der eigenen Lücken); im Übungsmodus, sobald alle 8 Lücken gefüllt sind. Pflichtenheft Punkt 6 angepasst (bestätigt 27.11.2026).

### Geändert
- Datei heißt im Repository `index.html` statt `luecke_v1.0.html`; online unter https://henningschmidt1.github.io/lueckentext/?rolle=A (bzw. `B`, `solo`).

