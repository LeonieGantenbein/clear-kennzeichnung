# Factsheet: CLEAR auf einen Blick

Das Factsheet fasst alle Kürzel und Regeln von CLEAR zusammen. Es dient als Nachschlagehilfe und kann einem Sprachmodell als Prompt übergeben werden, damit dieses seine Beteiligung an einem Text nach CLEAR ausweist.

## Notation

```
CLEAR (Rolle): C?, L?, E(p|n)?, A: Modelle, Zeitraum, R?
```

- Pro Achse wird die höchste erreichte Stufe angegeben; sie schliesst die darunterliegenden ein.
- Jede beteiligte Person erhält eine eigene Zeile.
- Die Kennzeichnung steht vor oder nach dem Text.

## Kürzel

| Kürzel | Bedeutung |
|---|---|
| **C** | **Conception – Konzeption und Gedankengang** |
| C0 | Der Gedankengang ist ausschliesslich menschlich entwickelt. |
| C1 | Die KI diente bei der Konzeption als Gesprächspartnerin. |
| C2 | Einzelne inhaltliche Teile wurden von der KI ausgearbeitet. |
| C3 | Der Inhalt wurde umfassend von der KI erzeugt. |
| **L** | **Language – sprachliche Bearbeitung** |
| L0 | Die Sprache ist ohne KI formuliert. |
| L1 | Korrektorat: Rechtschreibung, Grammatik und Zeichensetzung. |
| L2 | Stillektorat: Formulierungen verbessert, Inhalt unverändert. |
| L3 | Tiefenlektorat: Eingriffe in Aufbau und Argumentation. |
| L4 | Übersetzung durch die KI. |
| **E** | **Evidence – Quellen und ihre Verarbeitung** |
| E0 | Quellenzugang und -erschliessung ohne KI. |
| E1 | Quellenzugang: Die KI findet, beschafft oder übersetzt Quellen; der Mensch liest und deutet sie. |
| E2 | Quellenerschliessung: Die KI fasst Quellen zusammen; weitergearbeitet wird mit den Zusammenfassungen. |
| E3 | Quelleninterpretation: Die Deutung der Quellen durch die KI wurde übernommen. |
| E4 | Ergebnisinterpretation: Ein Schluss der KI erscheint im Text als Ergebnis. |
| (p) | Publiziertes, für Lesende nachprüfbares Material. |
| (n) | Eigenes, unpubliziertes Material. |
| **A** | **Attribution – Ausweisung:** eingesetzte KI-Modelle und Zeitraum der Nutzung. |
| **R** | **Responsibility – Rechenschaft** |
| R1 | Vollständig geprüft und vom Menschen verantwortet. |
| R2 | Stichprobenartig geprüft und daher nicht vollständig verantwortet. |
| R3 | Ungeprüft veröffentlicht und von niemandem verantwortet. |

## Prompt für die Selbstauskunft eines Sprachmodells

Der folgende Text kann am Ende einer Zusammenarbeit in denselben Chat kopiert werden. Das Modell schlägt daraufhin eine Kennzeichnung vor und begründet sie.

```
Bitte kennzeichne nach CLEAR, wie du an diesem Text beteiligt warst. Stütze dich ausschliesslich auf unseren bisherigen Chatverlauf.

Gib für jede Achse die höchste erreichte Stufe an und begründe sie in einem Satz:

C – Konzeption: C0 Gedankengang ausschliesslich menschlich · C1 KI als Gesprächspartnerin · C2 einzelne inhaltliche Teile von der KI ausgearbeitet · C3 Inhalt umfassend von der KI erzeugt
L – Sprache: L0 ohne KI · L1 Korrektorat · L2 Stillektorat (Formulierungen, Inhalt unverändert) · L3 Tiefenlektorat (Aufbau und Argumentation) · L4 Übersetzung
E – Evidenz: E0 ohne KI · E1 Quellenzugang (finden, beschaffen, übersetzen) · E2 Quellenerschliessung (Zusammenfassungen ersetzen die Primärquelle) · E3 Quelleninterpretation übernommen · E4 Schluss der KI als Ergebnis übernommen; Zusatz (p) publiziertes, (n) eigenes unpubliziertes Material
A – Ausweisung: dein Modellname und der Zeitraum unserer Zusammenarbeit
R – Rechenschaft: Lass R offen. Diese Angabe kann nur der Mensch machen.

Format: CLEAR (Rolle): C?, L?, E(p|n)?, A: Modell, Zeitraum, R?
Bei L gilt die tiefste Beteiligung, nicht die häufigste. Wenn du eine Stufe aus dem Verlauf nicht sicher bestimmen kannst, sage das, statt zu raten.
```

## Grenzen der Selbstauskunft

Eine Selbstauskunft des Modells ist nur aussagekräftig, wenn die gesamte Arbeit mit einem einzigen Sprachmodell in einem einzigen Chatverlauf stattgefunden hat. Nur dann überblickt das Modell den vollständigen Arbeitsprozess. Wurden mehrere Chats, Werkzeuge oder Modelle verwendet, wurde der Text ausserhalb des Chats überarbeitet oder ist der Verlauf so lang, dass frühere Teile nicht mehr erfasst sind, kann das Modell seine Beteiligung nicht vollständig beurteilen. Die Einstufung ist dann von der Person selbst vorzunehmen.

Auch im günstigsten Fall bleibt die Angabe des Modells ein Vorschlag, den der Mensch prüft und gegebenenfalls korrigiert. Die Rechenschaft (R) kann nur der Mensch übernehmen.

---

[Zurück zur Übersicht](README.md) · [Spezifikation](SPEZIFIKATION.md) · [Kultur vor Kennzeichnung](KULTUR.md) · English: [FACTSHEET.en.md](FACTSHEET.en.md)
