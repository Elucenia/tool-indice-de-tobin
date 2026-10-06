<!-- ELUCENIA technical documentation · indice-de-tobin · de · no clinical/professional/rights approval -->

# Tobin-Index (Index für schnelle flache Atmung)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/indice-de-tobin)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Spontane Atemfrequenz

`fr`

Atemzüge/min · Bereich: 1–80

### Spontanes Atemzugvolumen

`vt`

mL · Bereich: 50–1500

## Fassung der Methode

RSBI/Yang–Tobin 1991: f/VT, VT in Litern; nicht mit VT in mL verwechseln

## Dokumentierte Formel

f/VT = Atemfrequenz (Atemzüge/min) ÷ Atemzugvolumen (Liter).

## Grenzen und Population

RSBI wurde als Prädiktor des Ergebnisses von Beatmungsentwöhnungsversuchen untersucht. Das Ergebnis hängt von Messbedingungen und -technik ab und bestätigt allein weder Atemwegsschutzfähigkeit noch Extubationssicherheit. Ein günstiger Index bedeutet keinen garantierten Erfolg.

## Referenzen

- [Yang KL, Tobin MJ. A prospective study of indexes predicting the outcome of trials of weaning from mechanical ventilation. N Engl J Med, 1991.](https://doi.org/10.1056/NEJM199105233242101)

- [Boles JM et al. Weaning from mechanical ventilation. Eur Respir J, 2007.](https://doi.org/10.1183/09031936.00010206)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Unter 105: begünstigt das Gelingen des Weanings


### 2

105 oder mehr: sagt ein Weaning-Versagen voraus


### 3

105 oder mehr: sagt ein Weaning-Versagen voraus

