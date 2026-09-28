# SÄUREN_LAB

**Säuren in Lebensmitteln – Beispiel 1: Speiseessig**

Erster technischer Prototyp des didaktischen Spin-offs zum bestehenden TITRATIONSTOOL.

## Version 0.1.0

Umgesetzt sind die Phasen 1–4 des Referenzpfads:

1. **pH untersuchen** – Indikatorpapier, eigener Schätzwert, genauere virtuelle Elektrodenmessung, Grundfragen und Aussagekraft des pH-Werts.
2. **Vermuten** – Vorhersage zur portionsweisen Zugabe von NaOH; optionale Neutralisations-Simulationen.
3. **Messen** – diskontinuierliche NaOH-Zugabe, Messwerttabelle und wachsende Punktwolke. `+0,2 mL` wird rechtzeitig vor dem steilen Kurvenbereich sichtbar freigeschaltet.
4. **Kurve entdecken** – freie Beschreibung der Punktwolke, danach erst „Punkte verbinden“, Reflexion der ursprünglichen Vermutung und optionale automatische Titration mit Reglern für Zugabemenge und Geschwindigkeit.

## Chemisches Modell

Referenzfall:

- 10,0 mL Essigsäurelösung
- c(CH3COOH) = 0,083 mol/L
- c(NaOH) = 0,100 mol/L
- pKs(Essigsäure) = 4,76
- 25 °C

Der pH-Wert wird für jeden Mischzustand aus einer Ladungsbilanz für das System Essigsäure/Acetat/NaOH numerisch berechnet. Der Äquivalenzbereich liegt im Modell bei etwa 8,3 mL NaOH.

## Didaktische Prinzipien

- keine fertige Titrationskurve zu Beginn
- Messpunkte entstehen einzeln und werden zunächst nicht verbunden
- jede nicht passende Antwort erhält eine kurze fachliche Erklärung statt nur „falsch“
- Protokollierung des Lernwegs
- keine automatische Benotung
- GitHub-Pages-tauglich, keine externen Bibliotheken nötig

## GitHub Pages

Die Dateien können direkt in die Root-Ebene eines GitHub-Repositories gelegt werden:

- `index.html`
- `README.md`
- `.nojekyll`

Danach unter **Settings → Pages** die Veröffentlichung aus dem gewünschten Branch aktivieren.

## Nächste geplante Schritte

- Phase 5: steilen Kurvenbereich und Äquivalenzpunkt qualitativ erkennen
- Phase 6: 1. Ableitung als Hilfe zum Auffinden des ÄP
- Phase 7: Bromthymolblau und Phenolphthalein im Graphen vergleichen
- Phase 8–10: Realversuch planen, optionale Videos/Verlinkung zum TITRATIONSTOOL, geführte Auswertung bis zur Angabe „5 % Säure“
