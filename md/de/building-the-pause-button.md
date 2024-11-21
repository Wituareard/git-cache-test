

---
title: Die Pause-Taste bauen
description: Wie würde eine KI-Pause aussehen? Wie kann man tatsächlich die Schaffung einer Superintelligenz verhindern?
---
Wenn wir die Schaffung einer superintelligenten KI zulassen, riskieren wir jedes einzelne Leben auf der Erde.
Wenn wir über eine Pause sprechen, sprechen wir über die Umsetzung eines internationalen Verbots der Schaffung einer superintelligenten KI.
Einige argumentieren, dass es zu früh ist, die Pause-Taste zu drücken (wir [tun es nicht](/urgency)), aber die meisten Experten scheinen sich einig zu sein, dass es gut sein könnte, eine Pause einzulegen, wenn die Entwicklungen zu schnell voranschreiten.
Aber bisher haben wir keine Pause-Taste.
Also sollten wir anfangen, darüber nachzudenken, wie das funktionieren würde und wie wir es umsetzen können.

## Das Rennen: Warum wir internationale Zusammenarbeit benötigen {#the-race-why-we-need-international-cooperation}

Wir erwarten nicht, dass ein einzelnes Land in der Lage ist, eine Pause umzusetzen.
Die wirtschaftlichen Anreize sind zu stark, und die Verlangsamung der KI-Entwicklung würde ein Land in einen wirtschaftlichen und geopolitischen Nachteil bringen.
Die Kosten einer Unterinvestition in Sicherheit sind global verteilt, während die Vorteile einer Beschleunigung lokal sind.
Dieses spieltheoretische Problem wird manchmal als "Moloch" oder ein "Rennen nach unten" bezeichnet.

Der einzige Ausweg ist ein internationales Abkommen.
Deshalb sind wir so besessen von [Gipfeltreffen](/summit): Diese sind die Veranstaltungen, bei denen globale Entscheidungsträger zusammenkommen und an einer globalen Lösung arbeiten.
Oder zumindest ist das, was wir wollen, dass sie tun.
Bisher haben alle KI-Sicherheitsgipfeltreffen nicht zu einer sinnvollen Regulierung geführt.
Es liegt an Ihnen und mir, [sie zu überzeugen](/action).

## Compute-Governance {#compute-governance}

Um ein Spitzen-LLM (wie GPT-4) zu trainieren, benötigt man eine Menge hochspezialisierter und teurer Hardware.
GPT-4 wurde auf 25.000 Nvidia A100-GPUs trainiert, die jeweils 10.000 Dollar kosten.
Und viele erwarten, dass KI-Modelle in Zukunft noch größer werden.

Die schiere Skalierung moderner KI-Trainingsanforderungen ist immens.
Microsoft hat kürzlich einen Plan angekündigt, ein [Kernkraftwerk zu bauen](https://www.theverge.com/2024/9/20/24249770/microsoft-three-mile-island-nuclear-power-plant-deal-ai-data-centers), um seine KI-Strombedürfnisse zu decken.
Glücklicherweise bedeutet dies, dass KI-Trainingsläufe schwer zu verstecken sind, zumindest in naher Zukunft.

Durch die Kontrolle und Überwachung der KI-Chip-Lieferkette können Regierungen oder andere Regulierungsbehörden sicherstellen, dass niemand einen gefährlichen KI-Trainingslauf startet.
Lassen Sie uns in die verschiedenen Engpässe in dieser Lieferkette eintauchen.

### Engpässe in der Chip-Lieferkette {#choke-points-in-the-chip-supply-chain}

Es ist schwer, die Komplexität und Interdependenz der KI-Chip-Lieferkette zu übertreiben.
Sie besteht aus verschiedenen hochspezialisierten Unternehmen, von denen einige die einzigen auf der Welt sind, die bestimmte Komponenten produzieren können.
Das ist eine gute Nachricht für die Regulierung.
Durch die Hardware können wir die Trainingsläufe regulieren.
Lassen Sie uns in die verschiedenen Engpässe in der KI-Chip-Lieferkette eintauchen.

#### Silizium-Wafer: Shin-Etsu, Sumco, Siltronic {#silicon-wafers-shin-etsu-sumco-siltronic}

#### Lithografie: ASML & SMEE {#lithography-asml--smee}

Alle modernen Chips werden unter Verwendung von Lithografiemaschinen hergestellt: riesige Maschinen, die jeweils 200 Millionen Dollar kosten und Licht auf einen Silizium-Wafer projizieren.
Dieser Lithografioprozess ist einer der komplexesten und teuersten Teile des Chip-Herstellungsprozesses.
Spitzen-KI-Chips werden alle unter Verwendung von EUV-Lithografie hergestellt, und ASML ist das einzige Unternehmen, das diese Maschinen herstellt.
Dieses niederländische Unternehmen ist einer der wichtigsten potenziellen Engpässe für die KI-Regulierung.
Diese Maschinen sind unglaublich komplex und erfordern viel Expertise, um sie zu bauen und zu warten.
Bemerkenswert ist, dass sie [Fernabschaltungen](https://www.businessinsider.com/asml-tsmc-semiconductor-chip-equipment-kill-switch-china-invade-taiwan-2024-5) haben (hauptsächlich für den Fall, dass Taiwan angegriffen wird), also ist die Pause-Taste in gewisser Weise bereits eingebaut.

Die niederländische Regierung hat strenge Exportkontrollen für ihre EUV-Lithografiemaschinen eingerichtet, die Exportgenehmigungen erfordern.
Diese Exportkontrollen wurden hauptsächlich eingerichtet, um Chinas Chip-Ambitionen zu verlangsamen.
Die [USA, Japan und die Niederlande](https://apnews.com/article/technology-district-of-columbia-netherlands-china-business-6801d6c5f65b0bc1df6186e2e89a6f7d) haben ein (nicht öffentliches) Abkommen geschlossen, um Chip- und Lithografie-Exporte nach China zu beschränken.

Das chinesische Unternehmen SMEE versucht, aufzuholen, aber es ist nicht in der Lage, eigene EUV-Maschinen herzustellen.
Ihre DUV-Maschinen sind [immer noch bei 28nm](https://www.scmp.com/tech/big-tech/article/3278235/chinese-chip-making-shows-progress-new-euv-patent-domestic-lithography-champion) stecken, was Generationen hinter ASMLs 5nm-EUV-Prozess zurückliegt, geschweige denn ASMLs kommende 2nm-Maschinen.
Also ist SMEE nicht in der Lage, moderne KI-Chips zu produzieren.

Mit anderen Worten: ASML ist ein grundlegender Engpass in der KI-Chip-Lieferkette.

#### Optik: Zeiss {#optics-zeiss}

ASMLs EUV-Maschinen verwenden Spiegel und Linsen von dem deutschen Unternehmen Zeiss.
Im Jahr 2016 kaufte ASML [25%](https://optics.org/news/7/11/11) von Zeiss, und die beiden Unternehmen haben eine sehr enge Beziehung.
Es ist wahrscheinlich, dass kein anderes Unternehmen in der Lage ist, diese Optik zu produzieren.

#### Interconnect & Packaging: ASE {#interconnect--packaging-ase}

Wenn ein Chip-Die eine Fabrik verlässt, muss es "verpackt" werden.
ASE ist wahrscheinlich das größte Interconnect-Unternehmen für KI-Chips.

#### Fertigung: TSMC, Samsung und SMIC {#fabrication-tsmc-samsung-amd-smic}

Der Bau einer "Fab" (einer Chip-Fabrik) ist erstaunlich schwierig: Sie hat eine Null-Toleranz für Staubpartikel, erfordert die teuersten High-Tech-Geräte und hat eine sehr komplexe Lieferkette.
Eine moderne Fab kostet etwa 10 bis 20 Milliarden Dollar.

Die Taiwan Semiconductor Manufacturing Company produziert etwa 90% der modernen KI-Chips, die alle bei 7nm-Präzision oder besser hergestellt werden.
Samsung ist das einzige andere Unternehmen, das moderne KI-Chips produzieren kann.

Aber das chinesische Unternehmen SMIC holt schnell auf - es hat bereits einen funktionsfähigen 7nm-Prozess.
Aufgrund von US- und NL-Exportkontrollen kann SMIC keine ASML-EUV-Maschinen kaufen und ist jetzt auch bei dem Kauf von älteren DUV-Maschinen eingeschränkt.
Im Juni 2024 zeigte ein [Bericht](https://evertiq.com/news/55926), dass SMIC 5nm-Chips unter Verwendung von DUV-Hardware produzieren kann,
und jetzt in der Lage ist, 7nm-KI-Chips zu produzieren (etwa drei Jahre hinter dem 4nm-Prozess, den ASMLs EUV-Maschinen produzieren können), aber SMICs Lithografie ist von niedrigen Ausbeuten geplagt.

#### Speicherfertigung: Micron, SK Hynix {#memory-fabrication-micron-sk-hynix}

KI-Chips benötigen eine Menge HBMs (High-Bandwidth-Memory), die der fortschrittlichste Speichertyp ist.
Nur wenige Unternehmen können sie produzieren.

#### KI-Chip-Design: Nvidia, AMD, Intel, Google, Apple {#ai-chip-design-nvidia-amd-intel-google-apple}

Die bekanntesten Unternehmen auf dieser Seite sind alle Chip-Designer.
Und es gibt neue Unternehmen wie Cerebras und Groq, die Chips speziell für KI entwerfen.
Bemerkenswert ist, dass einige dieser Unternehmen relativ veraltete Prozesse verwenden, um ihre Chips zu produzieren, wie Groq, das 14nm verwendete, was ein potenzieller Engpass für die Regulierung ist.

### On-Chip-Governance {#on-chip-governance}

Der Artikel ["Sichere, regierbare Chips"](https://www.cnas.org/publications/reports/secure-governable-chips) schlägt einen neuen Ansatz für die KI-Regulierung vor.

### Verifizierungsmethoden - Verhinderung großer Trainingsläufe {#verification-methods---preventing-large-training-runs}

Jetzt, da wir verschiedene Engpässe in der Chip-Lieferkette identifiziert haben, können wir anfangen, darüber nachzudenken, wie wir große Trainingsläufe verhindern können.
Diese oben genannten Akteure können unter Druck gesetzt werden (von Regierungen), um sicherzustellen, dass ihre Produkte nicht für gefährliche KI-Trainingsläufe verwendet werden.

Aber wie kann dies verifiziert werden?

Das Papier ["Verifizierungsmethoden für internationale KI-Abkommen"](https://arxiv.org/abs/2408.16074) listet verschiedene Optionen auf:

1. **Fernerkundung**: Verwendet Satelliten- und Infrarot-Bildgebung, um Rechenzentren durch visuelle und thermische Signaturen zu erkennen. Hochgradig machbar, aber durch Tarnung oder unterirdische Anlagen begrenzt.
2. **Whistleblower**: Verlässt sich auf Insider, die Nicht-Compliance melden, die durch rechtliche und finanzielle Schutzmaßnahmen motiviert werden. Machbar, aber abhängig von Insider-Zugang und -Bereitschaft, Informationen preiszugeben.
3. **Energie-Überwachung**: Verfolgt den Stromverbrauch, um große KI-Operationen zu identifizieren, machbar, wenn Muster eindeutig sind. Machbarkeit variiert; Daten können durch andere hochenergetische Aktivitäten verschleiert werden.
4. **Zoll-Daten-Analyse**: Überwacht den Import/Export von KI-Hardware auf Anomalien. Machbar, insbesondere für Importe, obwohl Länder mit inländischer Produktion möglicherweise nicht erkannt werden.
5. **Finanz-Intelligence**: Beobachtet große oder ungewöhnliche Transaktionen im Zusammenhang mit KI-Hardware-Käufen. Machbar, wenn Finanz-Privatsphäre und Bankgesetze es zulassen, oft am besten in Kombination mit anderen Methoden.
6. **Rechenzentrum-Inspektionen**: Physische Standort-Inspektionen, um die Einhaltung von Hardware-Beschränkungen und Sicherheitsprotokollen zu überprüfen. Effektiv, wenn das Gastland Inspektionen zulässt; invasiv und ressourcenintensiv.
7. **Halbleiter-Fertigungsanlagen-Inspektionen**: Überprüft die Einhaltung von Chip-Produktionsvorschriften durch Inspektionen von Anlagen mit relevanten Geräten. Machbar, aber erfordert erhebliche Ressourcen und die Zustimmung des Gastlandes.
8. **KI-Entwickler-Inspektionen**: Überprüft Einrichtungen auf autorisierten Code, Sicherheitsprotokolle und KI-Evaluierungsdaten. Effektiv, aber hochinvasiv, erfordert spezialisierte Expertise und die Kooperation des Landes.
9. **Chip-Standort-Verfolgung**: Verfolgt die Bewegungen von KI-Chips, um deren Einsatz zu überwachen. Machbar mit internationalen Abkommen, aber umgehbar durch Deaktivierung der Verfolgung oder Spoofing von Standortdaten.
10. **Chip-basierte Berichterstattung**: Integriert Berichtsmechanismen in Chips, um zu warnen, wenn diese über autorisierte Grenzen hinaus verwendet werden. Machbar, aber herausfordernd, erfordert internationale Standards und Hardware-Entwicklung; umgehbar durch Modifikation der Firmware.

Jede Methode hat ihre Stärken und Schwächen, erfordert oft komplementäre Ansätze oder internationale Zusammenarbeit für eine effektive Umsetzung.

Andere vorgeschlagene Methoden umfassen:

1. **[flexHEGs](https://yoshuabengio.org/wp-content/uploads/2024/09/FlexHEG-Interim-Report_2024.pdf)**: Eine neue Art von Chip, der so programmiert werden kann, dass er sich selbst zerstört, wenn bestimmte Bedingungen erfüllt sind.

Eine internationale Institution könnte eingerichtet werden, um diese Verifizierungsmethoden zu überwachen und die Pause durchzusetzen.

## Software-Governance {#software-governance}

Physische Chips sind unser primärer Fokus, aber wir möchten auch die _Software_ regulieren, die zum Trainieren und Ausführen von KI-Modellen verwendet wird.
Es ist durchaus möglich, dass die größten Rechencluster ausreichend Leistung haben, um ein katastrophal gefährliches Modell zu trainieren, aber ihnen fehlt immer noch die Software.
Lassen Sie uns in die Arten von Software-Innovationen eintauchen, die wir unterscheiden können.

### Software-Innovationen {#software-innovations}

Zunächst gibt es _Trainings_-Innovationen.
Die Transformer-Architektur ermöglichte es beispielsweise KI-Modellen, viel leistungsfähiger zu sein, bei viel geringeren Kosten.
Das auf Transformer basierende ALBERT-Modell [übertraf](https://arxiv.org/pdf/2308.04950) das BERT-Modell, obwohl es aus 18-mal weniger Parametern bestand.
In Zukunft können wir noch effizientere Architekturen sehen.
Es gibt auch Innovationen bei den Daten, die einem Modell zugeführt werden.

Zusätzlich zu Trainingsverbesserungen haben wir verschiedene _Laufzeit_-Verbesserungen gesehen.
Chain-of-Thought, Graph-of-Thought und andere Techniken können drastische Verbesserungen in der Leistung von KI-Modellen bringen.
Tools wie AutoGPT können einfache Chatbots in vollständig autonome Agenten verwandeln, die das Web durchsuchen, E-Mails senden und andere Aufgaben ausführen.
OpenAIs o1-Modell ermöglicht größere Denkfähigkeiten, indem es mehr Zeit damit verbringt, über eine Antwort nachzudenken, bevor es sie liefert.

### Regulierung von Software {#regulating-software}

Die Software-Seite von KI ist schwieriger zu kontrollieren als die Hardware-Seite.
Software ist nur Information - sie kann leicht kopiert und verteilt werden.
Dennoch haben wir Informationen zuvor verboten.
Kinderpornografie ist beispielsweise illegal zu produzieren, zu verbreiten und zu besitzen.
Die gleichen Durchsetzungsmechanismen könnten verwendet werden, um gefährliche KI-Software zu regulieren.