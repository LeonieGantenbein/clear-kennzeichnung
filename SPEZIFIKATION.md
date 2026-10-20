# Spezifikation v1.0

## Ausgangslage

Technische Wasserzeichen werden die Transparenz von Texten nicht herstellen. Ein Wasserzeichen beantwortet allenfalls, ob ein KI-Modell beteiligt war, nicht aber, in welcher Weise. Über den Gehalt der Beteiligung, ihre Reichweite und die Frage, wer für den Text einsteht, sagt es nichts. Hat ein Mensch den Text verfasst und eine KI ihn lediglich geglättet, greift es gar nicht. Auch die KI-Verordnung der EU (AI Act) verlangt keine differenzierte Auskunft, sondern eine Kennzeichnung in wenigen, eng umrissenen Fällen.

Wo weder Regulierung noch Technik weiterhelfen, bleibt die freiwillige Offenlegung. CLEAR gliedert sie in fünf Angaben pro beteiligter Person.

## Die fünf Achsen

### C – Conception (Konzeption)

Die Achse C erfasst, wer den Gedankengang eines Textes entwickelt hat.

- **C0** – Der Gedankengang ist ausschliesslich menschlich entwickelt.
- **C1** – Die KI diente bei der Konzeption als Gesprächspartnerin.
- **C2** – Einzelne inhaltliche Teile wurden von der KI ausgearbeitet.
- **C3** – Der Inhalt wurde umfassend von der KI erzeugt.

### L – Language (sprachliche Bearbeitung)

Die Achse L erfasst, wie weit die KI in die sprachliche Gestalt eines Textes eingegriffen hat.

- **L0** – Die Sprache ist ohne KI formuliert.
- **L1** – Korrektorat: Die KI hat Rechtschreibung, Grammatik und Zeichensetzung korrigiert.
- **L2** – Stillektorat: Die KI hat Formulierungen verbessert, ohne den Inhalt zu verändern.
- **L3** – Tiefenlektorat: Die KI hat in Aufbau und Argumentation eingegriffen.
- **L4** – Übersetzung: Der Text wurde von der KI übersetzt.

### E – Evidence (Evidenz)

Die Achse E betrifft die Quellen, auf denen ein Text beruht. Ihre Stufen geben an, wie weit die KI zwischen Mensch und Material stand.

- **E0** – Zugang zu den Quellen und ihre Erschliessung erfolgten ohne KI.
- **E1** – Quellenzugang: Die KI hat Quellen gefunden, beschafft oder übersetzt; gelesen und gedeutet hat sie der Mensch.
- **E2** – Quellenerschliessung: Die KI hat Quellen gelesen und zusammengefasst, und es wurde mit diesen Zusammenfassungen statt mit den Primärquellen weitergearbeitet. Was dort fehlt, fehlt auch im Text.
- **E3** – Quelleninterpretation: Die KI hat gedeutet, was die Quellen besagen, was tragfähig ist und wo sie einander widersprechen; diese Deutung wurde übernommen.
- **E4** – Ergebnisinterpretation: Die KI hat aus den Ergebnissen einen Schluss gezogen, der im Text als Ergebnis erscheint.

Zusatz: **(p)** für publiziertes, **(n)** für eigenes, unpubliziertes Material.

Der Zusatz zeigt an, ob Lesende nachprüfen können, was geschehen ist: Bei (p) ist die Quelle zugänglich, bei (n) nicht. Eine Deutung der Stufe E(p)4 lässt sich früher oder später überprüfen. E(n)4 hingegen – eine von der KI vorgeschlagene Deutung eigener Daten – entzieht sich jeder Kontrolle von aussen. Gerade deshalb muss sie offengelegt werden.

### A – Attribution (Ausweisung)

Die Achse A nennt die verwendeten KI-Modelle und den Zeitraum ihrer Nutzung. Wer den Text Jahre später liest, kann so einordnen, mit welchem Stand der Werkzeuge er entstanden ist.

### R – Responsibility (Rechenschaft)

Die Achse R hält fest, ob ein Mensch für den Text einsteht.

- **R1** – Der Text wurde vollständig geprüft und wird vom Menschen verantwortet.
- **R2** – Der Text wurde stichprobenartig geprüft und wird daher nicht vollständig verantwortet.
- **R3** – Der Text wurde ungeprüft veröffentlicht und wird von niemandem verantwortet.

## Notation

```
CLEAR (Rolle): C?, L?, E(p|n)?, A: Modelle, Zeitraum, R?
```

- Angegeben wird pro Achse die höchste erreichte Stufe; sie schliesst die darunterliegenden ein.
- Jede beteiligte Person weist ihren eigenen Anteil aus und verantwortet ihn. Mehrere Beteiligte – etwa Autorin, Lektorat und Übersetzung – erhalten je eine eigene Zeile.
- Die Kennzeichnung steht vor oder nach dem Text.

## Beispiel

```
CLEAR (Autorin): C1, L3, E(p)1, A: Claude Opus 4.8, Fable 5, Opus 5, 04–09/2026, R1
```

Lesart: Der Gedankengang ist der eigene. Die KI diente als Sparringpartnerin – sie hat widersprochen, nachgefragt und Einwände formuliert, die Position aber nicht vorgegeben (C1). Beim Schreiben ging ihre Beteiligung über das Glätten hinaus und betraf den Aufbau, die Anordnung der Argumente und die Übergänge (L3). Die KI hat Quellenverweise recherchiert; sämtliche Quellen sind publiziert und nachprüfbar (E(p)1). Jede Stelle wurde geprüft und wird verantwortet (R1). Mehrere Modelle sind genannt, weil der Text über mehrere Monate entstanden ist.

## Hinweise zur Einstufung

Die Grenze zwischen L2 und L3 verläuft zwischen Formulierung und Argument. Wer einen überarbeiteten Text als Ganzes liest, sieht nur das Ergebnis und kann nicht mehr unterscheiden, was von ihm selbst stammt. Der Eindruck, es sei lediglich geglättet worden, führt deshalb systematisch zu einer zu niedrigen Einstufung.

Es empfiehlt sich, sprachliche Überarbeitungen durch KI stets im Korrekturmodus vornehmen zu lassen (Word: «Änderungen nachverfolgen»; Google Docs: Vorschlagsmodus; reiner Text: Vergleich der Fassungen) und die Vorschläge einzeln zu prüfen. Diese Anweisung lässt sich direkt in den Prompt aufnehmen.

- Finden sich Änderungen, die Sätze zusammenführen, die Reihenfolge umstellen oder ein Argument straffen, liegt L3 vor – unabhängig davon, wie viele rein stilistische Korrekturen daneben stehen. Die Achse misst die tiefste Beteiligung, nicht die häufigste.
- Wer jede Änderung einzeln bestätigt hat, hat den Text tatsächlich geprüft; R1 bleibt damit erreichbar.

## Umkehrung: CLEAR als Erwartungsprofil

CLEAR ist zunächst eine Selbstauskunft, lässt sich aber auch umkehren: Wer Texte entgegennimmt, kann mit denselben Angaben festlegen, was erwartet wird. Schulen, Maturitätsschulen und Hochschulen erhielten damit eine Sprache, die ihnen bislang fehlt. Ein Beispiel für Abschlussarbeiten:

| Achse | Vorgabe | Begründung |
|---|---|---|
| R | R1 verbindlich | Gleichsam eine Unterschrift; die einzige Stufe, die mit einer Prüfungsleistung vereinbar ist |
| L | bis L2, in schreibintensiven Fächern gegebenenfalls bis L3 | abhängig vom Fach |
| C | höchstens C1 | Der Gedankengang ist genau die Leistung, die geprüft wird |
| E | E1 | Quellenkritik ist das Handwerk, das eine Abschlussarbeit unter Beweis stellen muss |

Eine Institution, die dies festhält, verbietet keine Werkzeuge, sondern benennt Stufen und vermittelt den Umgang mit ihnen.

## Andere Medien (offen)

CLEAR ist für Texte entworfen. Für Bilder, Bewegtbilder und Code bedarf es einer angepassten Form; die Grundfrage bleibt dieselbe: Woran war die KI beteiligt, und wer steht dafür ein?

- A und R lassen sich unverändert übernehmen.
- Bild und Video: An die Stelle der Sprache tritt die Gestaltung (Retusche, Ergänzung, Erzeugung ganzer Bildteile). Bei dokumentarischem Material wird E zur Frage, ob das Gezeigte tatsächlich so stattgefunden hat.
- Code: An die Stelle der Sprache tritt die Umsetzung. E fragt nach übernommenen Bibliotheken und Codebeständen, R nach Tests und Review.

Wie die Stufen im Einzelnen auszugestalten sind, sollten jene erarbeiten, die mit diesen Medien arbeiten. Vorschläge sind willkommen.

## Grenzen

CLEAR ist noch in keiner Praxis erprobt oder evaluiert und mit Sicherheit unvollständig. Die Kennzeichnung beweist nichts; sie bleibt Selbstauskunft. Voraussetzung ihrer Wirksamkeit ist eine Kultur, in der Offenlegung nicht bestraft wird (→ Kapitel [«Kultur vor Kennzeichnung»](KULTUR.md)).

---

[Zurück zur Übersicht](README.md) · [Kultur vor Kennzeichnung](KULTUR.md) · [Factsheet](FACTSHEET.md) · English: [SPECIFICATION.md](SPECIFICATION.md)
