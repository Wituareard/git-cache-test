

---
title: Die Pause-Taste bauen
description: Wie würde eine AI-Pause aussehen? Wie kann man tatsächlich die Schaffung einer superintelligenten KI verhindern?
---

Wenn wir die Schaffung einer superintelligenten KI zulassen, riskieren wir jedes einzelne Leben auf der Erde.
Wenn wir über eine Pause sprechen, sprechen wir über die Umsetzung eines internationalen Verbots der Schaffung einer superintelligenten KI.
Einige argumentieren, dass es zu früh ist, die Pause-Taste zu drücken (wir [tun es nicht](/urgency)), aber die meisten Experten scheinen sich einig zu sein, dass es gut sein könnte, eine Pause einzulegen, wenn die Entwicklungen zu schnell voranschreiten.
Aber bisher haben wir keine Pause-Taste.
Also sollten wir anfangen, darüber nachzudenken, wie das funktionieren würde und wie wir es umsetzen können.

## Das Rennen: warum wir internationale Zusammenarbeit benötigen {#the-race-why-we-need-international-cooperation}

Wir erwarten nicht, dass ein einzelnes Land in der Lage ist, eine Pause umzusetzen.
Die wirtschaftlichen Anreize sind zu stark, und die Verlangsamung der KI-Entwicklung würde ein Land in einen wirtschaftlichen und geopolitischen Nachteil bringen.
Die Kosten einer zu geringen Investition in Sicherheit werden global verteilt, während die Vorteile einer Beschleunigung lokal sind.
Dieses spieltheoretische Problem wird manchmal als "Moloch" oder ein "Rennen nach unten" bezeichnet.

Der einzige Ausweg ist ein internationales Abkommen.
Deswegen sind wir so besessen von [Gipfeltreffen](/summit): das sind die Ereignisse, bei denen globale Entscheidungsträger zusammenkommen und an einer globalen Lösung arbeiten.
Oder zumindest, das ist es, was wir wollen, dass sie tun.
Bisher haben alle KI-Sicherheitsgipfeltreffen nicht zu einer sinnvollen Regulierung geführt.
Es liegt an Ihnen und mir, [sie zu überzeugen](/action).

## Mit einer internationalen KI-Behörde {#with-an-international-ai-authority}

Eine Pause-Taste würde bedeuten, dass es eine Institution gibt, die das Recht hat, sie zu drücken.
Diese Institution benötigt bestimmte Befugnisse:

- **Verifizierung**: Die Fähigkeit, zu überprüfen, dass keine superintelligente KI geschaffen wird. Wir werden darauf in einem späteren Abschnitt eingehen.
- **Durchsetzung**: Die Fähigkeit, die Pause durchzusetzen. Dies könnte durch die Verhängung von Sanktionen gegen Länder, die die Pause verletzen, oder durch die Beschlagnahme von Hardware, die zur Ausbildung einer superintelligenten KI verwendet wird, erfolgen.

## Ohne eine internationale KI-Behörde {#without-an-international-ai-authority}

Aber auch ohne eine solche Institution gibt es Dinge, die wir tun können

## Rechner-Regierungsführung {#compute-governance}

Um ein Spitzen-LLM (wie GPT-4) zu trainieren, benötigt man eine Menge hochspezialisierter und teurer Hardware.
GPT-4 wurde auf 25.000 Nvidia A100-GPUs trainiert, die jeweils 10.000 Dollar kosten.
Und viele erwarten, dass KI-Modelle in Zukunft noch größer werden.

### Engpässe in der Chip-Lieferkette {#choke-points-in-the-chip-supply-chain}

Es ist schwer, die Komplexität und Interdependenz der KI-Chip-Lieferkette zu übertreiben.
Das ist großartige Nachricht für die Regierungsführung.
Durch die Hardware können wir die Trainingsläufe regulieren.

#### ASML - der Lithographie-Engpass {#asml---the-lithography-bottleneck}

Alle modernen Chips werden mit Lithographiemaschinen hergestellt: riesigen Maschinen, die 200 Millionen Dollar kosten und Licht auf einen Siliziumwafer projizieren.
Dieser Lithographieprozess ist einer der komplexesten und teuersten Teile des Chip-Herstellungsprozesses.
Spitzen-KI-Chips werden alle mit EUV-Lithographie hergestellt, und ASML ist das einzige Unternehmen, das diese Maschinen herstellt.
Dieses niederländische Unternehmen ist einer der wichtigsten potenziellen Engpässe für die KI-Regierungsführung.
Die niederländische Regierung hat strenge Exportkontrollen für ihre EUV-Lithographiemaschinen eingerichtet,

#### SMIC - der chinesische Konkurrent, der aufholt {#smic---the-chinese-competitor-that-is-catching-up}

Das chinesische Unternehmen SMIC versucht, aufzuholen, aber es ist nicht in der Lage, eigene EUV-Maschinen herzustellen.
Aufgrund von US/NL-Exportkontrollen kann SMIC keine ASML-EUV-Maschinen kaufen und ist jetzt auch bei der Anschaffung der älteren DUV-Maschinen eingeschränkt.
Im Juni 2024 zeigte ein [Bericht](https://evertiq.com/news/55926), dass SMIC 5nm-Chips mit DUV-Hardware produzieren kann,
und jetzt in der Lage ist, 7nm-KI-Chips zu produzieren (etwa drei Jahre hinter dem 4nm-Prozess, den ASMLs EUV-Maschinen produzieren können), aber SMICs EUV-Lithographie ist von niedrigen Ausbeuten geplagt.

#### Zeiss: Spiegel und Linsen {#zeiss-mirrors--lensens}

ASMLs EUV-Maschinen verwenden Spiegel und Linsen von der deutschen Firma Zeiss.
Im Jahr 2016 kaufte ASML [25%](https://optics.org/news/7/11/11) von Zeiss, und die beiden Unternehmen haben eine sehr enge Beziehung.

### Verifizierungsmethoden - Verhinderung großer Trainingsläufe {#verification-methods---preventing-large-training-runs}

Jetzt, da wir verschiedene Engpässe in der Chip-Lieferkette identifiziert haben, können wir anfangen, darüber nachzudenken, wie wir große Trainingsläufe verhindern können.
Diese oben genannten Akteure können unter Druck gesetzt werden (von Regierungen), um sicherzustellen, dass ihre Produkte nicht für gefährliche KI-Trainingsläufe verwendet werden.

Aber wie kann dies überprüft werden?

Das Papier ["Verifizierungsmethoden für internationale KI-Abkommen"](https://arxiv.org/abs/2408.16074) listet verschiedene Optionen auf:

1. **Fernerkundung**: Verwendet Satelliten- und Infrarot-Bildgebung, um Rechenzentren durch visuelle und thermische Signaturen zu erkennen. Sehr machbar, aber begrenzt durch Tarnung oder unterirdische Anlagen.
2. **Whistleblower**: Verlässt sich auf Insider, die Nicht-Compliance melden, motiviert durch rechtliche und finanzielle Schutzmaßnahmen. Machbar, aber abhängig von Insider-Zugang und Bereitschaft zur Offenlegung.
3. **Energieüberwachung**: Verfolgt den Stromverbrauch, um große KI-Operationen zu identifizieren, machbar, wenn Muster eindeutig sind. Machbarkeit variiert; Daten können durch andere hochenergetische Aktivitäten verschleiert werden.
4. **Zoll-Daten-Analyse**: Überwacht den Import/Export von KI-Hardware auf Anomalien. Machbar, insbesondere für Importe, obwohl Länder mit inländischer Produktion möglicherweise nicht erkannt werden.
5. **Finanz-Intelligence**: Beobachtet große oder ungewöhnliche Transaktionen im Zusammenhang mit KI-Hardware-Käufen. Machbar, wenn Finanz-Privatsphäre und Bankgesetze es zulassen, oft am besten in Kombination mit anderen Methoden.
6. **Rechenzentrum-Inspektionen**: Physische Standort-Inspektionen, um die Einhaltung von Hardware-Grenzen und Sicherheitsprotokollen zu überprüfen. Effektiv, wenn das Gastland Inspektionen zulässt; invasiv und ressourcenintensiv.
7. **Halbleiter-Fertigungsanlagen-Inspektionen**: Überprüft die Einhaltung von Chip-Produktionsvorschriften durch Inspektionen von Anlagen mit relevanter Hardware. Machbar, aber erfordert erhebliche Ressourcen und die Zustimmung des Gastlandes.
8. **KI-Entwickler-Inspektionen**: Überprüft Einrichtungen auf autorisierten Code, Sicherheitsprotokolle und KI-Evaluierungsdaten. Effektiv, aber hochinvasiv, erfordert spezialisierte Expertise und die Kooperation des Landes.
9. **Chip-Standort-Verfolgung**: Verfolgt die Bewegung von KI-Chips, um ihre Verwendung zu überwachen. Machbar mit internationalen Abkommen, aber umgehbar durch Deaktivierung der Verfolgung oder Spoofing von Standortdaten.
10. **Chip-basierte Berichterstattung**: Integriert Berichtsmechanismen in Chips, um zu warnen, wenn sie über autorisierte Grenzen hinaus verwendet werden. Machbar, aber herausfordernd, erfordert internationale Standards und Hardware-Entwicklung; umgehbar durch Modifikation der Firmware.

Jede Methode hat ihre Stärken und Schwächen, erfordert oft komplementäre Ansätze oder internationale Zusammenarbeit für eine effektive Umsetzung.

Eine internationale Institution könnte eingerichtet werden, um diese Verifizierungsmethoden zu überwachen und die Pause durchzusetzen.

## Software-Regierungsführung {#software-governance}

Physische Chips sind unser Hauptaugenmerk, aber wir möchten auch die Software regulieren, die zur Ausbildung und Ausführung von KI-Modellen verwendet wird.
Es ist durchaus möglich, dass die größten Rechencluster ausreichend Leistung haben, um ein katastrophal gefährliches Modell zu trainieren, aber ihnen fehlt immer noch die Software.
Lassen Sie uns in die Arten von Software-Innovationen eintauchen, die wir unterscheiden können.

### Software-Innovationen {#software-innovations}

Erstens gibt es Innovationen bei der Ausbildung.
Die Transformer-Architektur ermöglichte es beispielsweise KI-Modellen, viel leistungsfähiger zu sein, bei viel geringeren Kosten.
Das auf Transformer basierende ALBERT-Modell [übertraf](https://arxiv.org/pdf/2308.04950) das BERT-Modell, obwohl es aus 18-mal weniger Parametern bestand.
In Zukunft können wir noch effizientere Architekturen sehen.
Es gibt auch Innovationen bei den Daten, die einem Modell zugeführt werden.

Zusätzlich zu den Ausbildungsverbesserungen haben wir verschiedene Laufzeitverbesserungen gesehen.
Chain-of-Thought, Graph-of-Thought und andere Techniken können drastische Verbesserungen in der Leistung von KI-Modellen bringen.
Tools wie AutoGPT können einfache Chatbots in vollständig autonome Agenten verwandeln, die das Web durchsuchen, E-Mails senden und andere Aufgaben ausführen.
OpenAIs o1-Modell ermöglicht größere Denkfähigkeiten, indem es dem Modell erlaubt, mehr Zeit damit zu verbringen, eine Antwort zu überdenken, bevor es sie liefert.

### Regulierung von Software {#regulating-software}

Die Software-Seite von KI ist schwieriger zu kontrollieren als die Hardware-Seite.
Software ist nur Information - sie kann sehr leicht kopiert und verteilt werden.
Dennoch haben wir Informationen zuvor verboten.
Kinderpornografie ist beispielsweise illegal zu erstellen, zu verbreiten und zu besitzen.
Die gleichen Durchsetzungsmechanismen könnten verwendet werden, um gefährliche KI-Software zu regulieren.