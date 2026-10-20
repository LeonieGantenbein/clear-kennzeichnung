# Spezifikation v1.0

## Ausgangslage

Technische Wasserzeichen werden die Transparenz von Texten nicht herstellen. Ein Wasserzeichen beantwortet nur, ob ein KI-Modell beteiligt war – nicht, inwiefern. Es sagt nichts über den Gehalt, die Reichweite der Beteiligung oder darüber, wer für den Text einsteht. Wo ein Mensch verfasst und eine KI nur geglättet hat, greift es gar nicht. Auch der EU AI Act verlangt keine differenzierte Auskunft, sondern eine Kennzeichnung in wenigen eng umrissenen Fällen.

Wo Pflicht und Technik ausfallen, bleibt die freiwillige Offenlegung. CLEAR besteht aus fünf Angaben pro beteiligtem Akteur.

## Die fünf Achsen

### C – Conception (Konzeption)

- **C0** rein menschlich entwickelter Gedankengang
- **C1** KI als Diskussionspartner bei der Konzeption
- **C2** Ausarbeitung von einzelnen inhaltlichen Teilen durch KI
- **C3** umfassend durch KI generierter Inhalt

### L – Language (sprachliche Bearbeitung)

- **L0** rein menschlich formulierte Sprache ohne KI
- **L1** Korrektorat durch KI
- **L2** Stillektorat durch KI: sprachliche Verbesserung der Formulierungen, ohne den Inhalt zu verändern
- **L3** Tiefenlektorat mit Eingriffen in Aufbau und Argumentation durch KI
- **L4** Übersetzung durch KI

### E – Evidence (Evidenz)

Die Quellen, auf denen der Text ruht. Die Stufen geben an, wie weit die KI zwischen Mensch und Material stand.

- **E0** Quellenzugang und -erschliessung ohne KI
- **E1** Quellenzugang: KI hat Quellen gefunden, beschafft oder übersetzt; gelesen und gedeutet hat der Mensch
- **E2** Quellenerschliessung: KI hat gelesen und zusammengefasst, und mit diesen Zusammenfassungen wurde weitergearbeitet statt mit der Primärquelle – was dort fehlt, fehlt auch im Text
- **E3** Quelleninterpretation: KI hat gedeutet, was die Quellen besagen, was tragfähig ist und was einander widerspricht, und diese Deutung wurde übernommen
- **E4** Ergebnisinterpretation: KI hat aus dem Ergebnis einen Schluss gezogen, und dieser Schluss steht im Text als Ergebnis

Zusatz: **(p)** publiziertes Material · **(n)** eigenes, nicht publiziertes Material.

Er sagt, ob Lesende nachprüfen können, was geschehen ist. Bei (p) kann man zur Quelle gehen, bei (n) nicht. E(p)4 fällt früher oder später auf; E(n)4 – eine von der KI vorgeschlagene Deutung eigener Daten – fällt nie auf. Genau deshalb muss sie offengelegt werden.

### A – Attribution (Ausweisung)

Verwendete KI-Modelle und Zeitraum. Wer den Text in zehn Jahren liest, weiss so, welchem Stand der Werkzeuge er gegenübersteht.

### R – Responsibility (Rechenschaft)

- **R1** vollständig geprüft und durch den Menschen verantwortet
- **R2** stichprobenhaft geprüft und deshalb nicht vollständig durch den Menschen verantwortet
- **R3** ungeprüft veröffentlicht und deshalb von niemandem verantwortet

## Notation

```
CLEAR (Rolle): C?, L?, E(p|n)?, A: Modelle, Zeitraum, R?
```

- Pro Achse nur die höchste erreichte Stufe; sie schliesst die darunterliegenden ein.
- Jede beteiligte Person weist ihren eigenen Anteil aus und verantwortet ihn. Mehrere Beteiligte (Autorin, Lektorat, Übersetzung …) erhalten je eine eigene Zeile.
- Die Kennzeichnung steht vor oder nach dem Text.

## Beispiel

```
CLEAR (Autorin): C1, L3, E(p)1, A: Claude Opus 4.8, Fable 5, Opus 5, 04–09/2026, R1
```

Gelesen: Der Gedankengang ist der eigene, die KI war Sparringpartner – sie hat widersprochen, nachgefragt, Einwände geliefert, aber die Position nicht vorgegeben (C1). Beim Schreiben ging ihre Beteiligung über Glättung hinaus: Aufbau, Umstellung von Argumenten, Übergänge (L3). Die KI hat Quellenverweise herausgesucht; alle Quellen sind publiziert und nachprüfbar (E(p)1). Jede Stelle wurde geprüft und wird verantwortet (R1). Mehrere Modelle, weil der Text über Monate entstanden ist.

## Einstufungshilfe

Die Grenze zwischen L2 und L3 ist die Grenze zwischen Formulierung und Argument. Wer einen überarbeiteten Text im Ganzen liest, sieht nur das Ergebnis und kann nicht mehr sagen, was von ihm stammt. Das Gefühl, alles sei nur geglättet worden, führt systematisch zu einer zu niedrigen Einstufung.

Praktischer Rat: Sprachliche Überarbeitungen durch KI immer im Korrekturmodus vornehmen lassen (Word: Änderungen nachverfolgen; Google Docs: Vorschlagsmodus; reiner Text: Vergleich der Fassungen) und die Vorschläge einzeln durchgehen. Diese Anweisung lässt sich in den Prompt aufnehmen.

- Finden sich Änderungen, die Sätze zusammenlegen, Reihenfolgen tauschen oder ein Argument straffen, ist es L3 – unabhängig davon, wie viele reine Stilkorrekturen danebenstehen. Die Achse misst die tiefste Beteiligung, nicht die häufigste.
- Wer jede Änderung einzeln bestätigt hat, hat den Text tatsächlich geprüft: R1 bleibt erreichbar.

## Umkehrung: CLEAR als Erwartungsprofil

CLEAR ist zunächst Selbstauskunft, lässt sich aber umdrehen: Wer Texte entgegennimmt, kann mit denselben Angaben sagen, was erwartet wird. Für Schulen, Maturitätsschulen und Hochschulen wäre das eine Sprache, die bisher fehlt. Beispiel für Abschlussarbeiten:

| Achse | Vorgabe | Begründung |
|---|---|---|
| R | R1 zwingend | Eine Art Unterschrift; die einzige Stufe, die sich mit einer Prüfungsleistung verträgt |
| L | bis L2, in schreibintensiven Fächern evtl. bis L3 | je nach Fach |
| C | höchstens C1 | Der Gedankengang ist genau die Leistung, die geprüft wird |
| E | E1 | Quellenkritik ist das Handwerk, das eine Abschlussarbeit vorführen muss |

Eine Institution, die das so festhält, verbietet keine Werkzeuge, sondern benennt Stufen und lehrt den Umgang mit ihnen.

## Andere Medien (offen)

CLEAR ist für Texte entworfen. Für Bilder, Bewegtbilder und Code braucht es eine abgewandelte Form. Die Grundfrage bleibt: Woran war die KI beteiligt, und wer steht dafür ein?

- A und R lassen sich unverändert übernehmen.
- Bild/Video: An die Stelle der Sprache tritt die Gestaltung (Retusche, Ergänzung, Erzeugung ganzer Bildteile). Bei dokumentarischem Material wird E zur Frage, ob das Gezeigte so stattgefunden hat.
- Code: An die Stelle der Sprache tritt die Umsetzung. E fragt nach übernommenen Bibliotheken und Codebeständen, R nach Tests und Review.

Wie die Stufen im Einzelnen aussehen, sollten jene ausarbeiten, die mit diesen Medien arbeiten. Vorschläge sind willkommen.

## Grenzen

CLEAR ist noch in keiner Praxis erprobt oder evaluiert und mit Sicherheit unvollständig. Die Kennzeichnung beweist nichts; sie bleibt Selbstauskunft. Voraussetzung für ihre Wirksamkeit ist eine Kultur, in der Offenlegung nicht bestraft wird → Kapitel [«Kultur vor Kennzeichnung»](KULTUR.md).

---

[Zurück zur Übersicht](README.md) · [Kultur vor Kennzeichnung](KULTUR.md) · English: [SPECIFICATION.md](SPECIFICATION.md)
