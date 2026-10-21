# Factsheet: CLEAR auf einen Blick

Das Factsheet fasst alle Kürzel und Regeln auf einer Seite zusammen. Sie können es zum Nachschlagen nutzen oder einem Sprachmodell übergeben, damit es seine Beteiligung an einem Text nach CLEAR vorschlägt.

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
| (t) | Von der KI übersetzt. Eine reine Übersetzung gilt bereits als Korrektorat: L(t)1. |
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
| R3 | Ungeprüft veröffentlicht, mit dem Risiko, den Text trotzdem verantworten zu müssen. |

## Prompt für die Selbstauskunft eines Sprachmodells

Ein Sprachmodell kann seine Beteiligung selbst vorschlagen. Kopieren Sie dazu den folgenden Text am Ende einer Zusammenarbeit in denselben Chat. Das Modell schlägt dann für C, L, E und A eine Stufe vor und begründet sie; R setzen immer Sie.

```
Bitte kennzeichne nach CLEAR, wie du an diesem Text beteiligt warst. Stütze dich ausschliesslich auf unseren bisherigen Chatverlauf.

Gib für jede Achse die höchste erreichte Stufe an und begründe sie in einem Satz:

C – Konzeption: C0 Gedankengang ausschliesslich menschlich · C1 KI als Gesprächspartnerin · C2 einzelne inhaltliche Teile von der KI ausgearbeitet · C3 Inhalt umfassend von der KI erzeugt
L – Sprache: L0 ohne KI · L1 Korrektorat · L2 Stillektorat (Formulierungen, Inhalt unverändert) · L3 Tiefenlektorat (Aufbau und Argumentation); Zusatz (t), wenn du den Text übersetzt hast (reine Übersetzung: L(t)1)
E – Evidenz: E0 ohne KI · E1 Quellenzugang (finden, beschaffen, übersetzen) · E2 Quellenerschliessung (Zusammenfassungen ersetzen die Primärquelle) · E3 Quelleninterpretation übernommen · E4 Schluss der KI als Ergebnis übernommen; Zusatz (p) publiziertes, (n) eigenes unpubliziertes Material
A – Ausweisung: dein Modellname und der Zeitraum unserer Zusammenarbeit
R – Rechenschaft: Lass R offen. Diese Angabe kann nur der Mensch machen.

Format: CLEAR (Rolle): C?, L?, E(p|n)?, A: Modell, Zeitraum, R?
Bei L gilt die tiefste Beteiligung, nicht die häufigste. Wenn du eine Stufe aus dem Verlauf nicht sicher bestimmen kannst, sage das, statt zu raten.
```

## Grenzen der Selbstauskunft

Ein Modell kann nur beurteilen, was es gesehen hat. Seine Auskunft ist deshalb nur aussagekräftig, wenn die ganze Arbeit mit einem einzigen Sprachmodell in einem einzigen Chat stattgefunden hat.

Haben Sie mehrere Chats, Werkzeuge oder Modelle verwendet, den Text ausserhalb des Chats überarbeitet, oder ist der Verlauf so lang, dass das Modell die Anfänge nicht mehr erfasst, kann es seine Beteiligung nicht vollständig beurteilen. Nehmen Sie die Einstufung dann selbst vor.

Auch im besten Fall bleibt die Angabe des Modells ein Vorschlag, den Sie prüfen und, wo nötig, korrigieren. Die Rechenschaft (R) kann nur ein Mensch übernehmen.

---

[Zurück zur Übersicht](README.md) · [Spezifikation](SPEZIFIKATION.md) · [Kultur vor Kennzeichnung](KULTUR.md) · [Beispiele](BEISPIELE.md) · English: [FACTSHEET.en.md](FACTSHEET.en.md)
