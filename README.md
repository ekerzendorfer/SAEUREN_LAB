# SÄUREN_LAB v0.4.2 – Zwischenstand, Statistik und Pilotversion

## Neu in v0.4.2

### Statistische Serienauswertung

Nach Abschluss einer Titrationsserie und nach der eigenen Auswahl der verwendeten Messwerte werden zusätzlich angezeigt:

- Anzahl der ausgewählten Werte `n`
- Mittelwert
- **Stichproben-Standardabweichung `s`** mit `n − 1` im Nenner
- Spannweite

Die Statistik erscheint bewusst erst **nach** der Abgabe des selbst berechneten Mittelwerts und liefert damit keine vorzeitige Hilfe bei der Auswahl der Messwerte.

### Lokaler Zwischenstand

Im Kopfbereich stehen nun zur Verfügung:

- **Zwischenstand speichern**
- **Fortsetzen**
- **Speicher löschen**

Gespeichert wird ausschließlich im lokalen Browserspeicher (`localStorage`) des verwendeten Browsers. Es werden keine Daten an einen Server übertragen.

Gespeichert werden unter anderem:

- aktueller Lernweg und freigeschaltete Phasen
- Antworten und Eingaben
- Messreihen
- Arbeitsprotokoll
- Titrationschallenge und bereits abgeschlossene Serienläufe

Ein gerade laufender Autotitrations- oder Challenge-Titrationslauf muss vor dem Speichern beendet bzw. pausiert werden.

## Empfohlener nächster Schritt

Die chemischen Inhalte werden vorerst **nicht** um weitere Lebensmittelproben erweitert. Die App soll zunächst mit echten SchülerInnen erprobt werden. Rückmeldungen zu Verständlichkeit, Bedienung, Challenge, Hilfen und Zeitbedarf sollen in die nächste Überarbeitung einfließen.

## Später vorgemerkt

Die Titrationschallenge kann mit relativ geringem Aufwand als eigenständige kleine App ausgekoppelt werden. Denkbare, bewusst begrenzte weitere Szenarien:

- starke Säure + starke Base
- starke Base + starke Säure
- schwache Base + starke Säure
- wenige kuratierte Indikatoren

Der Fokus soll auch dort auf Bürettenbedienung, Endpunkterkennung, Wiederholungsmessung und Messwertbeurteilung liegen – nicht auf einem universellen Titrationssimulator.
