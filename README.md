# SÄUREN_LAB v0.2.1

Browserbasierter Lernweg **„Säuren in Lebensmitteln“**. Das Referenzbeispiel Speiseessig führt von einer einfachen pH-Bestimmung schrittweise zur Titrationskurve.

## Aktueller Stand

Enthalten sind die Phasen 1–7:

1. pH mit Indikatorpapier schätzen und genauer nachmessen
2. Vermutung zur Zugabe von NaOH formulieren
3. diskontinuierlich messen, Messwerttabelle und CSV-Export
4. aus Einzelpunkten die Titrationskurve entwickeln; Autotitration mit Pause, Zugabemenge und Geschwindigkeit
5. steilen Kurvenbereich markieren und Äquivalenzpunkt schätzen
6. Äquivalenzpunkt mit einer gemeinsam eingeblendeten Hilfskurve (1. Ableitung) lokalisieren
7. Umschlagsbereiche von Bromthymolblau und Phenolphthalein vergleichen

### Neu in v0.2.1

- pH-Kurve und Hilfskurve der 1. Ableitung liegen in **einem gemeinsamen, größeren Diagramm**
- zweite y-Achse als relative Skala der pH-Änderung
- Hilfskurve wird unabhängig von der zuvor gewählten Messpunktdichte auf einem feinen Volumenraster ausgewertet
- für einen didaktisch gut erkennbaren, aber nicht künstlich nadelförmigen Peak wird die mittlere pH-Änderung über ein kleines symmetrisches Volumenfenster betrachtet
- Maximum wird direkt im gemeinsamen Diagramm angeklickt
- transparente Erklärung, dass die Hilfskurve eine Auswertungshilfe und keine zusätzliche Messung ist

Falsche Antworten erhalten kurze fachliche Rückmeldungen und führen zu einem erneuten Versuch.

## GitHub Pages

`index.html` und `.nojekyll` können direkt in die Root-Ebene eines GitHub-Repositories gelegt werden.

## Nächster Ausbau

Phase 8–10: Probenvorbereitung des realen Speiseessigs, optionaler Realversuch/Video bzw. Übergang zum großen TITRATIONSTOOL und geführte Auswertung bis zur Etikettangabe „5 % Säure“. Eine Titrationschallenge ist anschließend vorgesehen.
