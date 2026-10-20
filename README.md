# CLEAR

**Kennzeichnung von KI-Beteiligung an Texten**

*Conception · Language · Evidence · Attribution · Responsibility*

Leonie Gantenbein · Version 1.0 · 2026

Lizenz: [CC BY 4.0](LICENSE.md) – frei nutzbar und veränderbar unter Namensnennung der Urheberin.<br>
URL: https://github.com/LeonieGantenbein/clear-kennzeichnung

English version: [README.en.md](README.en.md)

## Überblick

CLEAR ist ein Vorschlag, die Beteiligung künstlicher Intelligenz an Texten freiwillig und differenziert offenzulegen. An die Stelle des pauschalen Etiketts «KI-generiert» treten fünf Angaben. Sie halten fest, an welchen Arbeitsschritten eine KI mitgewirkt hat, wie weit ihr Anteil reicht und wer für das Ergebnis einsteht. Jede beteiligte Person macht diese Angaben für ihren eigenen Anteil. Wie eine Quellenangabe ist CLEAR damit keine Wertung, sondern eine Auskunft über die Entstehung eines Textes.

> **Zuerst die Kultur, dann die Kennzeichnung.**<br>
> Eine Kennzeichnung entfaltet nur dort Wirkung, wo Offenlegung nicht bestraft wird. Solange eine ehrliche Angabe den eigenen Text abwertet, kennzeichnet nur, wer es sich leisten kann, und Schweigen bleibt die rationale Wahl. CLEAR setzt deshalb eine kulturelle Verständigung voraus, die erst noch zu führen ist. → Kapitel [«Kultur vor Kennzeichnung»](KULTUR.md)

## Kurzreferenz

| Achse | Gegenstand | Stufen |
|---|---|---|
| **C** – Conception | Konzeption und Gedankengang | C0 ausschliesslich menschlich · C1 KI als Gesprächspartnerin · C2 einzelne inhaltliche Teile von der KI ausgearbeitet · C3 Inhalt umfassend von der KI erzeugt |
| **L** – Language | Sprachliche Bearbeitung | L0 ohne KI · L1 Korrektorat · L2 Stillektorat · L3 Tiefenlektorat (Aufbau und Argumentation) · L4 Übersetzung |
| **E** – Evidence | Quellen und ihre Verarbeitung | E0 ohne KI · E1 Quellenzugang · E2 Quellenerschliessung · E3 Quelleninterpretation · E4 Ergebnisinterpretation; Zusatz (p) publiziertes, (n) unpubliziertes Material |
| **A** – Attribution | Ausweisung der Werkzeuge | eingesetzte KI-Modelle und Zeitraum der Nutzung |
| **R** – Responsibility | Rechenschaft | R1 vollständig geprüft und verantwortet · R2 stichprobenartig geprüft · R3 ungeprüft, ohne verantwortliche Person |

Pro Achse wird die **höchste erreichte Stufe** angegeben; sie schliesst die darunterliegenden ein. Jede beteiligte Person – etwa Autorin, Lektorat oder Übersetzung – erhält eine eigene Zeile. Die Kennzeichnung steht vor oder nach dem Text.

**Beispiel:**

```
CLEAR (Autorin): C1, L3, E(p)1, A: Claude Opus 4.8, Fable 5, Opus 5, 04–09/2026, R1
```

Die vollständige Beschreibung aller Stufen, Hinweise zur Einstufung und die Anwendung in Bildungsinstitutionen enthält das Kapitel [«Spezifikation»](SPEZIFIKATION.md).

Alle Kürzel auf einen Blick sowie einen Prompt, mit dem ein Sprachmodell seine eigene Beteiligung ausweisen kann, enthält das [«Factsheet»](FACTSHEET.md).

## Status

CLEAR ist ein Vorschlag, der noch in keiner Praxis erprobt oder evaluiert wurde, und er ist mit Sicherheit unvollständig. Rückmeldungen, Erfahrungen aus der Anwendung sowie Vorschläge für Bilder, Bewegtbilder und Code sind ausdrücklich willkommen – über die [Issues dieses Repositorys](https://github.com/LeonieGantenbein/clear-kennzeichnung/issues).

## Herkunft

CLEAR wurde im Buch [*Zwischen Prompt und Welt. Über das Leben mit KI*](https://www.schwabe.ch/produkt/leonie-gantenbein-zwischen-prompt-und-welt-9783796556333-t-20562) von Leonie Gantenbein entwickelt, das im Dezember 2026 im Schwabe Verlag erscheint. Es knüpft an Begriffe aus [*Annetzung. Handeln durch Technologie und Imagination*](https://doi.org/10.24894/978-3-7965-5360-8) (2025) an, insbesondere an den Begriff der Welttransparenz: den Anspruch, zu wissen, ob einem Tatsächliches, Computergeneriertes oder Imaginiertes gegenübertritt.

## Zitieren

Gantenbein, Leonie (2026): CLEAR – Kennzeichnung von KI-Beteiligung an Texten. Version 1.0. https://github.com/LeonieGantenbein/clear-kennzeichnung

Maschinenlesbare Zitierangaben: [CITATION.cff](CITATION.cff) (auf GitHub über «Cite this repository»)

## Lizenz

[CC BY 4.0](LICENSE.md) – frei nutzbar und veränderbar, unter Namensnennung von Leonie Gantenbein.

---

Grundlage: Buchtext – `CLEAR (Autorin): C1, L3, E(p)1, A: Claude Opus 4.8, Fable 5, Opus 5, 04–09/2026, R1`<br>
Aufbereitung und sprachliche Überarbeitung für dieses Repository (Kürzung, Umstrukturierung, Zusammenfassung in KULTUR.md) – `CLEAR (Autorin): C2, L3, E(n)2, A: Claude Opus 5.5, 09–10/2026, R1`
