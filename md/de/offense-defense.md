

---
title: Angriff-Abwehr-Gleichgewicht in der KI-Sicherheit
description: Wie man über das Gleichgewicht zwischen Angriff und Abwehr in der KI-Sicherheit nachdenkt
---

Das Angriff-Abwehr-Gleichgewicht bezieht sich auf die relativen Stärken und Schwächen von Angriffs- und Abwehrstrategien, normalerweise im Kontext von militärischen Konflikten oder Sportwettbewerben.

Da KI eine Dual-Use-Technologie ist, können wir diese Angriff-Abwehr-Gleichgewichte in verschiedenen KI-Sicherheitsproblemen beobachten:

- Erstellung gefälschter Medien, Erkennung gefälschter Medien
- Cyberangriffe, Cyberabwehr
- KI-Übernahme, KI-Abwehr gegen Übernahme

Wie wird sich das Angriff-Abwehr-Gleichgewicht in der KI-Sicherheit entwickeln?

## Gefälschte Medien {#fake-media}

Moderne große Sprachmodelle können Texte in allen möglichen Stilen erstellen, und andere Modelle können Bilder, Audio- und sogar Videodateien erstellen.
Viele Modelle erstellen unüberzeugende Fälschungen, aber die Qualität verbessert sich rapide.

State-of-the-Art-Text-, Audio- und Bildmodelle sind bereits gut genug, um die meisten Menschen zu täuschen.
Im Jahr 2022 gewann das erste KI-generierte Bild einen Kunstwettbewerb.
Ein paar Monate später wurde ein Fotowettbewerb mit einem KI-generierten Bild gewonnen.

Wir haben auch KIs, die Deepfakes erkennen können.
Dies führt zu einem Katz-und-Maus-Spiel zwischen den Fälschern und den Detektoren.

Für Texte scheint die Angriffsseite zu gewinnen.
OpenAI [stellte](https://news.ycombinator.com/item?id=36862850) ihren KI-Klassifizierer aufgrund geringer Genauigkeit ein.

Glücklicherweise können Maßnahmen wie [Wasserzeichen](https://arxiv.org/abs/2303.07205) und digitale Signaturen verwendet werden, um Fälschungen zu erkennen.
Die Anforderung von Signaturen für alle Medien, die wir konsumieren, könnte eine geeignete Lösung sein.

## Cyberangriffe vs. Abwehr {#cybersecurity-attacks-vs-defenses}

Moderne große Sprachmodelle können verwendet werden, um Schwachstellen in Software zu finden.
Wenn Sie eine Schwachstelle entdecken, können Sie sie beheben (Abwehr) oder ausnutzen (Angriff).
Und glücklicherweise sind die meisten Menschen auf der Abwehrseite.

Es gibt jedoch einige Vorteile, die Angreifer gegenüber Verteidigern haben:

- **Angreifer müssen nur eine Schwachstelle finden, während Verteidiger alle finden müssen.** Die Verteidiger werden nicht wissen, welche Schwachstelle die Angreifer finden werden, daher müssen sie sich gegen alle verteidigen.
- **Das Bereitstellen von Patches dauert länger als ein Angriff.** Das "Window of Vulnerability" ist die Zeit, die von der Entdeckung eines Exploits bis zur Bereitstellung eines Patches vergeht. Verteidiger müssen den Fehler beheben, die Anwendung neu kompilieren oder die aktualisierten Bibliotheken veröffentlichen, und dann müssen alle Benutzer ihre Software aktualisieren. Dies kann Monate dauern, und in der Zwischenzeit kann die Schwachstelle ausgenutzt werden.

## Biohazards und Biodefense {#biohazards-and-biodefense}

KI kann verwendet werden, um neue biologische Agenzien zu entwerfen oder bei der Entwicklung einer Pandemie zu helfen.
Eine Gruppe von Studenten konnte einen Chatbot verwenden, um [alle Schritte zu erstellen, die benötigt werden, um eine neue Pandemie zu erstellen](https://arxiv.org/abs/2306.03809).
Es kann jedoch auch verwendet werden, um neue Impfstoffe, Medikamente oder Abwehrmittel gegen biologische Agenzien zu entwickeln.

- **Viren verbreiten sich schneller als Impfstoffe**. Ein Virus ist buchstäblich eine selbstreplizierende Maschine. Eine Impfung hingegen erfordert viel Aufwand, um sie herzustellen und zu verteilen.

## Unbekannte Technologie und Risiken {#unknown-technology-and-risks}

Eine KI, die weit intelligenter ist als Menschen, kann ihre überlegene Verständnis der Realität nutzen, um neue Technologien zu entwickeln.
Vielleicht einige selbstreplizierende Nanobots, die alle Materie in Kopien von sich selbst umwandeln können, oder kleine Maschinen, die die Gehirne von Menschen beeinflussen können.
Es ist unmöglich, genau vorherzusagen, was für eine Technologie dies sein wird (wir müssten mindestens so intelligent sein wie die KI), aber wir können immer noch über das Angriff-Abwehr-Gleichgewicht nachdenken.
Die Schlussfolgerung ist nicht schwer: wir haben keine Ahnung, was kommt, und wir haben keine Ahnung, wie wir uns dagegen verteidigen können.
Wir sind im Nachteil.

## Schlussfolgerung {#conclusion-2}

Viele KI-Risiken haben ein Angriff-Abwehr-Gleichgewicht.
Für gefälschte Medien könnten wir digitale Signaturen verwenden, um Fälschungen zu erkennen, und das Gleichgewicht zugunsten der Abwehr verschieben.
Für Cyberangriffe, Biohazards und unbekannte Technologie scheint die Angriffsseite im Vorteil zu sein.

Die wichtige politische Implikation daraus ist: [Lasst uns diese Technologie nicht erst entwickeln](/proposal).