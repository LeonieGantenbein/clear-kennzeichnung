# CLEAR

**Kennzeichnung von KI-Beteiligung an Texten**

*Conception · Language · Evidence · Attribution · Responsibility*

Leonie Gantenbein · Version 1.0 · 2026

Lizenz: [CC BY 4.0](LICENSE.md) – frei nutzbar und veränderbar unter Namensnennung der Urheberin.<br>
URL: https://github.com/LeonieGantenbein/clear-kennzeichnung

## Überblick

CLEAR ist ein Vorschlag zur freiwilligen Offenlegung, woran und wie weit eine Künstliche Intelligenz an einem Text beteiligt war – und wer dafür einsteht. Statt eines pauschalen Ja/Nein («KI-generiert») gibt CLEAR fünf Angaben pro beteiligter Person an, vergleichbar einer Quellenangabe: als Auskunft über das Handwerk.

> **Zuerst die Kultur, dann die Kennzeichnung.**<br>
> Eine Kennzeichnung allein genügt nicht. Solange Offenlegung bestraft wird, kennzeichnet nur, wer es sich leisten kann, und Verschweigen bleibt die vernünftige Wahl. CLEAR setzt eine kulturelle Verhandlung voraus, die noch nicht geführt ist. → Kapitel [«Kultur vor Kennzeichnung»](KULTUR.md)

## Kurzreferenz

| Achse | Bedeutung | Stufen |
|---|---|---|
| **C** – Conception | Konzeption, Gedankengang | C0 rein menschlich · C1 KI als Diskussionspartner · C2 einzelne inhaltliche Teile durch KI · C3 umfassend KI-generierter Inhalt |
| **L** – Language | Sprachliche Bearbeitung | L0 ohne KI · L1 Korrektorat · L2 Stillektorat · L3 Tiefenlektorat (Aufbau, Argumentation) · L4 Übersetzung |
| **E** – Evidence | Quellen, auf denen der Text ruht | E0 ohne KI · E1 Quellenzugang · E2 Quellenerschliessung · E3 Quelleninterpretation · E4 Ergebnisinterpretation; Zusatz (p) publiziert / (n) nicht publiziert |
| **A** – Attribution | Ausweisung | verwendete KI-Modelle und Zeitraum |
| **R** – Responsibility | Rechenschaft | R1 vollständig geprüft und verantwortet · R2 stichprobenhaft geprüft · R3 ungeprüft, von niemandem verantwortet |

Pro Achse wird nur die **höchste erreichte Stufe** angegeben. Jede beteiligte Person (Autorin, Lektorat, Übersetzung …) erhält eine eigene Zeile. Die Kennzeichnung steht vor oder nach dem Text.

**Beispiel:**

```
CLEAR (Autorin): C1, L3, E(p)1, A: Claude Opus 4.8, Fable 5, Opus 5, 04–09/2026, R1
```

Vollständige Beschreibung aller Stufen, Einstufungshilfen und Anwendung in Bildungsinstitutionen: Kapitel [«Spezifikation»](SPEZIFIKATION.md)

## Status

CLEAR ist noch in keiner Praxis erprobt oder evaluiert und mit Sicherheit unvollständig. Rückmeldungen, Erfahrungen aus der Anwendung und Vorschläge für Bild, Video und Code sind willkommen – über [Issues in diesem Repository](https://github.com/LeonieGantenbein/clear-kennzeichnung/issues).

## Herkunft

CLEAR entstammt dem Buch *Zwischen Prompt und Welt. Über das Leben mit KI* von Leonie Gantenbein (erscheint 2027 im Schwabe Verlag) und baut auf Begriffen aus [*Annetzung: Handeln durch Technologie und Imagination*](https://doi.org/10.24894/978-3-7965-5360-8) (2025) auf, insbesondere dem Begriff der Welttransparenz.

## Zitieren

Gantenbein, Leonie (2026): CLEAR – Kennzeichnung von KI-Beteiligung an Texten. Version 1.0. https://github.com/LeonieGantenbein/clear-kennzeichnung

Maschinenlesbare Zitierangaben: [CITATION.cff](CITATION.cff) (auf GitHub über «Cite this repository»)

## Lizenz

[CC BY 4.0](LICENSE.md) – frei nutzbar und veränderbar, unter Namensnennung von Leonie Gantenbein.

---

Grundlage: Buchtext – `CLEAR (Autorin): C1, L3, E(p)1, A: Claude Opus 4.8, Fable 5, Opus 5, 04–09/2026, R1`<br>
Aufbereitung für dieses Repository (Kürzung, Umstrukturierung, Zusammenfassung in KULTUR.md) – `CLEAR (Autorin): C2, L3, E(n)2, A: Claude Opus 5.5, 09–10/2026, R1`
