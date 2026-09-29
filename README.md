# SÄUREN_LAB v0.4.0a – Challenge-Testpatch

Dieser Patch reserviert **v0.4.1 weiterhin für den späteren 4er-Serienmodus** und verbessert zunächst den Einzellauf.

## Änderungen

- direkter Einstieg über **„Titrationschallenge direkt“** im Kopfbereich
- Challenge bleibt zusätzlich als Weg C in Phase 9 erhalten
- Challenge-Raster wächst nicht mehr mit der Auswertung; Apparatur besitzt eine feste Höhe
- Bürette etwas höher und schmäler
- Rührstäbchen bleibt optisch horizontal und simuliert Rotation durch perspektivische Längenänderung
- Hahnskala klar beschriftet:
  - geschlossen
  - tropfenweise
  - langsamer Fluss
  - schneller Fluss
- aktueller Hahnzustand wird separat angezeigt
- Anfangsstand, Endstand und Differenz stehen kompakt in **einer Tabelle**
- Prüfschaltflächen liegen nebeneinander unter der Tabelle und werden erst bei sinnvoller Eingabe aktiv
- alle erklärenden Rückmeldungen zur Ablesung und Differenz erscheinen im rechten Beobachtungsrahmen
- Meniskus-Zoom und bestehende Scorelogik bleiben erhalten

## Für später vorgemerkt

- v0.4.1: 4er-Serie (1 Orientierung + 3 Bestimmungen), keine Nullstellung zwischen den Läufen
- Browser-Zwischenspeicher / Fortsetzen per localStorage, sobald die Challenge-Struktur stabil ist
- optischer Feinschliff der Phenolphthalein-Schlieren
