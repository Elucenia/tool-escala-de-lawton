<!-- ELUCENIA technical documentation · escala-de-lawton · de · no clinical/professional/rights approval -->

# Lawton-Brody-Skala (IADL)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/escala-de-lawton)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Telefon

`tel`

- `a` — Benutzt das Telefon selbstständig (sucht und wählt Nummern)
- `b` — Wählt einige bekannte Nummern
- `c` — Nimmt ab, wählt aber nicht
- `d` — Benutzt das Telefon nicht

### Einkaufen

`compras`

- `a` — Erledigt alle Einkäufe selbstständig
- `b` — Erledigt nur kleinere Einkäufe selbstständig
- `c` — Benötigt für jeden Einkauf eine Begleitperson
- `d` — Kann keine Einkäufe erledigen

### Zubereitung von Mahlzeiten

`comida`

- `a` — Plant, bereitet und serviert angemessene Mahlzeiten selbstständig
- `b` — Bereitet Mahlzeiten zu, wenn die Zutaten bereitgestellt werden
- `c` — Wärmt fertige Mahlzeiten auf und serviert sie, ernährt sich jedoch nicht angemessen
- `d` — Benötigt andere, die Mahlzeiten zubereiten und servieren

### Hausarbeiten

`casa`

- `a` — Versorgt den Haushalt selbstständig oder mit gelegentlicher Hilfe bei schweren Aufgaben
- `b` — Erledigt leichte Aufgaben (Geschirr spülen, Bett machen)
- `c` — Erledigt leichte Aufgaben, hält aber keine angemessene Sauberkeit aufrecht
- `d` — Benötigt Hilfe bei allen Aufgaben
- `e` — Führt keine Hausarbeit aus

### Wäsche waschen

`roupa`

- `a` — Wäscht die gesamte eigene Kleidung
- `b` — Wäscht kleine Kleidungsstücke
- `c` — Die gesamte Wäsche wird von anderen gewaschen

### Fortbewegung

`transp`

- `a` — Benutzt öffentliche Verkehrsmittel oder fährt selbstständig Auto
- `b` — Nutzt allein Taxi oder Fahrdienst, aber keine öffentlichen Verkehrsmittel
- `c` — Benutzt öffentliche Verkehrsmittel mit Begleitung
- `d` — Fährt nur mit Taxi oder Auto und mit Unterstützung einer anderen Person
- `e` — Verlässt das Haus nicht

### Medikamente

`remedio`

- `a` — Nimmt Medikamente selbstständig in der richtigen Dosis und zur richtigen Zeit ein
- `b` — Nimmt Medikamente ein, wenn jemand die Dosen vorher vorbereitet
- `c` — Kann Medikamente nicht selbstständig einnehmen

### Finanzen

`dinheiro`

- `a` — Verwaltet die Finanzen selbstständig
- `b` — Erledigt Alltagseinkäufe, benötigt aber Hilfe bei Bankgeschäften und größeren Anschaffungen
- `c` — Kann nicht mit Geld umgehen

## Fassung der Methode

Lawton–Brody 1969: lokale Anpassung, 8 Bereiche 0–1, Gesamt 0–8 für beide Geschlechter; nicht die geschlechtsspezifische Originalfassung

## Dokumentierte Formel

Je Aktivität 1 (selbstständig) oder 0 (abhängig) nach der Stufe:

Telefon: 1 in den ersten drei.

Einkaufen und Mahlzeiten: 1 nur in der ersten.

Haushalt: 1 außer „beteiligt sich nicht“.

Wäsche: 1 in den ersten zwei.

Verkehrsmittel: 1 in den ersten drei.

Medikamente: 1 nur in der ersten.

Finanzen: 1 in den ersten zwei.

Gesamt 0 (abhängig) bis 8 (selbstständig).

## Grenzen und Population

Diese Lawton-Version beurteilt acht instrumentelle Aktivitäten und verwendet gemäß den HIGN-Hinweisen von 2019 eine Gesamtsumme von 0 bis 8 für alle Geschlechter; sie verwendet nicht die frühere Bewertung für Männer mit fünf Items. Die konsultierten Hinweise empfehlen das Instrument nicht für ältere Menschen in Einrichtungen. Antworten der Person oder einer Auskunftsperson beschreiben die wahrgenommene Funktion und belegen nicht die tatsächliche Ausführung jeder Aufgabe; sie können die Fähigkeiten über- oder unterschätzen und kleine Veränderungen übersehen. Dokumentieren Sie, wer geantwortet hat, und den Kontext der Beurteilung.

## Referenzen

- [Lawton MP, Brody EM. Assessment of older people: self-maintaining and instrumental activities of daily living. Gerontologist, 1969.](https://doi.org/10.1093/geront/9.3_Part_1.179)

- [HIGN,TryThis23,revised2019](https://hign.org/sites/default/files/2020-06/Try_This_General_Assessment_23.pdf)

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
