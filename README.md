# SÄUREN_LAB v0.4.1 – Titrationschallenge mit Serienmodus

## Neu: Serie 1 + 3

Neben dem bisherigen Einzellauf kann die Challenge nun als Serie mit vier Titrationen derselben Probe durchgeführt werden:

1. **Orientierungstitration**
2. **Bestimmung 1**
3. **Bestimmung 2**
4. **Bestimmung 3**

### Bürette

Die Bürette wird zwischen den Läufen **nicht automatisch auf 0,00 mL gestellt**. Der reale Endstand eines Laufs wird zum Ausgangspunkt des nächsten Laufs. Nur wenn für den nächsten Versuch nicht mehr genügend Reserve vorhanden wäre, wird die Bürette nachgefüllt – dabei startet sie bewusst nicht exakt bei 0,00 mL.

Damit müssen bei jedem Lauf erneut

- Anfangsstand,
- Endstand,
- und die Differenz = Verbrauch

bestimmt werden.

### Noch keine Bewertung während der Serie

Nach jedem Lauf wird nur der Messwert gespeichert. Es erscheinen noch

- keine Abweichung vom wahren Äquivalenzvolumen,
- keine Punkte,
- keine automatische Entscheidung über gute oder schlechte Werte.

Die Orientierungstitration darf bewusst gröber ausgeführt und auch überschritten werden.

### Messwertauswahl

Erst nach allen vier Läufen werden die Auswahlkästchen freigeschaltet. Die SchülerInnen entscheiden selbst, welche Werte in den Mittelwert eingehen.

Die Spalte **Abweichung** bleibt bis dahin leer.

Anschließend muss der Mittelwert der ausgewählten Verbrauchswerte **selbst berechnet und eingegeben** werden. Die App kontrolliert zunächst nur die Rechnung.

### Bewertung erst nach Abgabe

Erst nach korrekter Abgabe des Mittelwerts werden Abweichungen und Score sichtbar.

Maximal 100 Punkte:

- **70 Punkte Endpunkt & Serie**
  - 50 Punkte Genauigkeit des ausgewählten Mittelwerts
  - 20 Punkte Reproduzierbarkeit der ausgewählten Werte
- **20 Punkte Bürettenablesung**
- **10 Punkte Dosierstrategie**

Mögliche Auszeichnungen:

- Präziser Mittelwert
- Reproduzierbare Serie
- Präzise Ablesung
- FeindosiererIn
- Laborstrategie verbessert

### Direkter Trainingsmodus

Beim direkten Einstieg in die Challenge wird kein Transfer zu Phase 10 benötigt und daher ausgeblendet.

Im normalen Lernweg über Phase 9 kann dagegen der ausgewählte Serienmittelwert direkt als Messwert an Phase 10 übergeben werden.

## Weiter vorgemerkt

- Browser-Zwischenspeicher / Fortsetzen mit localStorage
- abschließender optischer Feinschliff der Apparatur und Indikatorschlieren
