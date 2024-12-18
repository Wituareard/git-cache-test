---
title: Die Pause-Taste bauen
description: Wie würde eine KI-Pause aussehen? Wie kann man tatsächlich verhindern, dass eine Superintelligenz geschaffen wird?
---
Wenn wir die Schaffung einer superintelligenten KI zulassen, riskieren wir jedes einzelne Leben auf der Erde.
Wenn wir über eine Pause sprechen, sprechen wir über die Umsetzung eines internationalen Verbots der Schaffung einer superintelligenten KI.
Einige argumentieren, dass es zu früh ist, die Pause-Taste zu drücken (wir haben keine Zeit zu verlieren), aber die meisten Experten sind sich einig, dass es gut sein könnte, eine Pause einzulegen, wenn die Entwicklungen zu schnell voranschreiten.
Bisher haben wir jedoch keine Pause-Taste.
Also sollten wir anfangen, darüber nachzudenken, wie das funktionieren würde und wie wir es umsetzen können.

## Das Rennen: Warum wir internationale Zusammenarbeit benötigen {#the-race-why-we-need-international-cooperation}

Wir erwarten nicht, dass ein einzelnes Land in der Lage ist, eine Pause umzusetzen.
Die wirtschaftlichen Anreize sind zu stark, und die Verlangsamung der KI-Entwicklung würde ein Land in einen wirtschaftlichen und geopolitischen Nachteil bringen.
Die Kosten einer Unterinvestition in Sicherheit sind global verteilt, während die Vorteile einer Beschleunigung lokal sind.
Dieses spieltheoretische Problem wird manchmal als "Moloch" oder ein "Rennen nach unten" bezeichnet.

Der einzige Ausweg ist ein internationales Abkommen.
Deshalb sind wir so besessen von Gipfeltreffen: Diese sind die Veranstaltungen, bei denen globale Entscheidungsträger zusammenkommen und an einer globalen Lösung arbeiten.
Bisher haben jedoch alle KI-Sicherheitsgipfel nicht zu einer sinnvollen Regulierung geführt.
Es liegt an Ihnen und mir, sie zu überzeugen.

## Compute-Governance {#compute-governance}

Um ein Spitzen-LLM (wie GPT-4) zu trainieren, benötigt man eine Menge hochspezialisierter und teurer Hardware.
GPT-4 wurde auf 25.000 Nvidia A100-GPUs trainiert, die jeweils 10.000 Dollar kosten.
Viele erwarten, dass KI-Modelle in Zukunft noch größer werden.

Die schiere Größe der modernen KI-Trainingsanforderungen ist enorm.
Microsoft hat kürzlich einen Plan angekündigt, ein Kernkraftwerk für seine KI-Strombedürfnisse zu bauen.
Glücklicherweise bedeutet dies, dass KI-Trainingsläufe schwer zu verstecken sind, zumindest in naher Zukunft.

Durch die Kontrolle und Überwachung der KI-Chip-Lieferkette können Regierungen oder andere Regulierungsbehörden sicherstellen, dass niemand einen gefährlichen KI-Trainingslauf startet.
Lassen Sie uns in die verschiedenen Engpässe in dieser Lieferkette eintauchen.

### Engpässe in der Chip-Lieferkette {#choke-points-in-the-chip-supply-chain}

Es ist schwer, die Komplexität und Interdependenz der KI-Chip-Lieferkette zu übertreiben.
Sie besteht aus verschiedenen hochspezialisierten Unternehmen, von denen einige die einzigen auf der Welt sind, die bestimmte Komponenten produzieren können.
Das ist großartig für die Regulierung.
Durch die Hardware können wir die Trainingsläufe regulieren.
Lassen Sie uns in die verschiedenen Engpässe in der KI-Chip-Lieferkette eintauchen.

#### Silizium-Wafer: Shin-Etsu, Sumco, Siltronic {#silicon-wafers-shin-etsu-sumco-siltronic}

#### Lithografie: ASML & SMEE {#lithography-asml--smee}

Alle modernen Chips werden unter Verwendung von Lithografiemaschinen hergestellt: riesige Maschinen, die 200 Millionen Dollar kosten und Licht auf einen Silizium-Wafer projizieren.
Dieser Lithografioprozess ist einer der komplexesten und teuersten Teile des Chip-Herstellungsprozesses.
Spitzen-KI-Chips werden alle unter Verwendung von EUV-Lithografie hergestellt, und ASML ist das einzige Unternehmen, das diese Maschinen herstellt.
Dieses niederländische Unternehmen ist einer der wichtigsten potenziellen Engpässe für die KI-Regulierung.
Diese Maschinen sind unglaublich komplex und erfordern viel Expertise, um sie zu bauen und zu warten.
Bemerkenswert ist, dass sie Fernabschaltungen haben (hauptsächlich für den Fall, dass Taiwan angegriffen wird), also ist die Pause-Taste in gewisser Weise bereits eingebaut.

Die niederländische Regierung hat strenge Exportkontrollen für ihre EUV-Lithografiemaschinen eingerichtet, die Exportgenehmigungen erfordern.
Diese Exportkontrollen wurden hauptsächlich eingerichtet, um Chinas Chip-Ambitionen zu verlangsamen.
Die USA, Japan und die Niederlande haben ein (nicht öffentliches) Abkommen geschlossen, um den Export von Chips und Lithografiemaschinen nach China zu beschränken.

Das chinesische Unternehmen SMEE versucht, aufzuholen, aber es ist nicht in der Lage, eigene EUV-Maschinen herzustellen.
Ihre DUV-Maschinen sind immer noch auf 28nm festgelegt, was Generationen hinter ASMLs 5nm-EUV-Prozess zurückliegt, geschweige denn ASMLs kommende 2nm-Maschinen.
Also ist SMEE nicht in der Lage, moderne KI-Chips zu produzieren.

Mit anderen Worten: ASML ist ein grundlegender Engpass in der KI-Chip-Lieferkette.

#### Optik: Zeiss {#optics-zeiss}

ASMLs EUV-Maschinen verwenden Spiegel und Linsen von der deutschen Firma Zeiss.
Im Jahr 2016 kaufte ASML einen 25%igen Anteil an Zeiss, und die beiden Unternehmen haben eine sehr enge Beziehung.
Es ist wahrscheinlich, dass kein anderes Unternehmen in der Lage ist, diese Optik zu produzieren.

#### Verbindung und Verpackung: ASE {#interconnect--packaging-ase}

Wenn ein Chip-Die eine Fabrik verlässt, muss es "verpackt" werden.
ASE ist wahrscheinlich das größte Verbindungunternehmen für KI-Chips.

#### Fertigung: TSMC, Samsung und SMIC {#fabrication-tsmc-samsung-amd-smic}

Der Bau einer "Fab" (einer Chip-Fabrik) ist erstaunlich schwierig: Sie hat null Toleranz für Staubpartikel, erfordert die teuersten High-Tech-Geräte und hat eine sehr komplexe Lieferkette.
Eine moderne Fab kostet etwa 10 bis 20 Milliarden Dollar.

Die Taiwan Semiconductor Manufacturing Company produziert etwa 90% der modernen KI-Chips, die alle bei 7nm-Präzision oder besser hergestellt werden.
Samsung ist das einzige andere Unternehmen, das moderne KI-Chips produzieren kann.

Aber das chinesische Unternehmen SMIC holt schnell auf - sie haben bereits einen funktionsfähigen 7nm-Prozess.
Aufgrund der Exportkontrollen der USA und der Niederlande kann SMIC keine ASML-EUV-Maschinen kaufen und ist nun auch bei der Anschaffung der älteren DUV-Maschinen eingeschränkt.
Im Juni 2024 zeigte ein Bericht, dass SMIC 5nm-Chips unter Verwendung von DUV-Hardware produzieren kann,
und jetzt in der Lage ist, 7nm-KI-Chips zu produzieren (etwa drei Jahre hinter dem 4nm-Prozess, den ASMLs EUV-Maschinen produzieren können), aber SMICs Lithografie ist von niedrigen Ausbeuten geplagt.

#### Speicherfertigung: Micron, SK Hynix {#memory-fabrication-micron-sk-hynix}

KI-Chips benötigen eine Menge HBMs (High-Bandwidth-Memory), die der fortschrittlichste Speichertyp ist.
Nur wenige Unternehmen können sie produzieren.

#### KI-Chip-Design: Nvidia, AMD, Intel, Google, Apple {#ai-chip-design-nvidia-amd-intel-google-apple}

Die bekanntesten Firmennamen auf dieser Seite sind alle Chip-Designer.
Und es gibt neue Unternehmen wie Cerebras und Groq, die Chips speziell für KI entwerfen.
Bemerkenswert ist, dass einige dieser Unternehmen relativ veraltete Prozesse verwenden, um ihre Chips zu produzieren, wie Groq, die 14nm verwendeten, was ein potenzieller Engpass für die Regulierung ist.

### On-Chip-Governance {#on-chip-governance}

- Der Artikel "Sichere, regierbare Chips" schlägt einen neuen Ansatz für die KI-Regulierung vor.
- Chips könnten auf Nachrichten von vertrauenswürdigen Servern reagieren, um zu beweisen, dass sie sich innerhalb einer bestimmten Entfernung von einem vertrauenswürdigen Ort befinden. Dies kann auf einige Kilometer genau sein.

### Verifizierungsmethoden - Verhinderung großer Trainingsläufe {#verification-methods---preventing-large-training-runs}

Jetzt, da wir verschiedene Engpässe in der Chip-Lieferkette identifiziert haben, können wir anfangen, darüber nachzudenken, wie wir große Trainingsläufe verhindern können.
Diese oben genannten Akteure können unter Druck gesetzt werden (von Regierungen), um sicherzustellen, dass ihre Produkte nicht für gefährliche KI-Trainingsläufe verwendet werden.

Aber wie kann dies verifiziert werden?

Das Papier "Verifizierungsmethoden für internationale KI-Abkommen" listet verschiedene Optionen auf:

1. **Fernerkundung**: Verwendet Satelliten- und Infrarot-Bildgebung, um Rechenzentren durch visuelle und thermische Signaturen zu erkennen. Hochgradig machbar, aber begrenzt durch Tarnung oder unterirdische Anlagen.
2. **Whistleblower**: Verlässt sich auf Insider, die Nicht-Compliance melden, die durch rechtliche und finanzielle Schutzmaßnahmen motiviert werden. Machbar, aber abhängig von Insider-Zugang und Bereitschaft zur Offenlegung.
3. **Energieüberwachung**: Verfolgt den Stromverbrauch, um große KI-Operationen zu identifizieren, machbar, wenn die Muster eindeutig sind. Machbarkeit variiert; Daten können durch andere hochenergetische Aktivitäten verschleiert werden.
4. **Zoll-Daten-Analyse**: Überwacht den Import/Export von KI-Hardware auf Anomalien. Machbar, insbesondere für Importe, obwohl Länder mit inländischer Fertigung möglicherweise nicht erkannt werden.
5. **Finanz-Intelligence**: Beobachtet große oder ungewöhnliche Transaktionen im Zusammenhang mit KI-Hardware-Käufen. Machbar, wenn Finanz-Privatsphäre und Bankgesetze es zulassen, oft am besten in Kombination mit anderen Methoden.
6. **Rechenzentrum-Inspektionen**: Physische Standort-Inspektionen, um die Einhaltung von Hardware-Grenzen und Sicherheitsprotokollen zu überprüfen. Effektiv, wenn das Gastland Inspektionen zulässt; invasiv und ressourcenintensiv.
7. **Halbleiter-Fertigungsanlagen-Inspektionen**: Überprüft die Einhaltung von Chip-Produktionsvorschriften durch Inspektionen von Anlagen mit relevanter Hardware. Machbar, aber erfordert erhebliche Ressourcen und die Zustimmung des Gastlandes.
8. **KI-Entwickler-Inspektionen**: Überprüft Einrichtungen auf autorisierten Code, Sicherheitsprotokolle und KI-Evaluierungsdaten. Effektiv, aber hochinvasiv, erfordert spezialisierte Expertise und die Kooperation des Landes.
9. **Chip-Standort-Verfolgung**: Verfolgt die Bewegungen von KI-Chips, um ihre Einsatzorte zu überwachen. Machbar mit internationalen Abkommen, aber umgehbar durch Deaktivierung der Verfolgung oder Spoofing von Standortdaten.
10. **Chip-basierte Berichterstattung**: Integriert Berichtsmechanismen in Chips, um zu warnen, wenn sie über autorisierte Grenzen hinaus verwendet werden. Machbar, aber herausfordernd, erfordert internationale Standards und Hardware-Entwicklung; umgehbar durch Modifikation der Firmware.

Jede Methode hat ihre Stärken und Schwächen, erfordert oft komplementäre Ansätze oder internationale Zusammenarbeit für eine effektive Umsetzung.

Andere vorgeschlagene Methoden umfassen:

1. **flexHEGs**: Eine neue Art von Chip, der so programmiert werden kann, dass er sich selbst zerstört, wenn bestimmte Bedingungen erfüllt sind.

Eine internationale Institution könnte eingerichtet werden, um diese Verifizierungsmethoden zu überwachen und die Pause durchzusetzen.

## Software-Governance {#software-governance}

Physische Chips sind unser Hauptaugenmerk, aber wir möchten auch die Software regulieren, die zum Trainieren und Ausführen von KI-Modellen verwendet wird.
Es ist durchaus möglich, dass die größten Rechencluster ausreichend Leistung haben, um ein katastrophal gefährliches Modell zu trainieren, aber ihnen immer noch die Software fehlt.
Lassen Sie uns in die Arten von Software-Innovationen eintauchen, die wir unterscheiden können.

### Software-Innovationen {#software-innovations}

Zunächst gibt es Trainings-Innovationen.
Die Transformer-Architektur beispielsweise ermöglichte es KI-Modellen, viel leistungsfähiger zu sein, bei viel geringeren Kosten.
Das auf Transformer basierende ALBERT-Modell übertraf das BERT-Modell, obwohl es aus 18-mal weniger Parametern bestand.
In Zukunft könnten wir noch effizientere Architekturen sehen.
Es gibt auch Innovationen bei den Daten, die einem Modell zugeführt werden.

Neben Trainingsverbesserungen haben wir verschiedene Laufzeitverbesserungen gesehen.
Chain-of-Thought, Graph-of-Thought und andere Techniken können drastische Verbesserungen in der Leistung von KI-Modellen bringen.
Tools wie AutoGPT können einfache Chatbots in vollständig autonome Agenten verwandeln, die das Web durchsuchen, E-Mails senden und andere Aufgaben ausführen.
OpenAIs o1-Modell ermöglicht größere Denkfähigkeiten, indem es dem Modell ermöglicht, mehr Zeit damit zu verbringen, eine Antwort zu überdenken, bevor es sie liefert.

### Regulierung von Software {#regulating-software}

Die Software-Seite der KI ist schwieriger zu kontrollieren als die Hardware-Seite.
Software ist nur Information - sie kann leicht kopiert und verteilt werden.
Dennoch haben wir Informationen zuvor verboten.
Kinderpornografie beispielsweise ist illegal zu produzieren, zu verbreiten und zu besitzen.
Die gleichen Durchsetzungsmechanismen könnten verwendet werden, um gefährliche KI-Software zu regulieren.