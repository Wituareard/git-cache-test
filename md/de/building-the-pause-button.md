

---
title: Die Pause-Taste bauen
description: Wie würde eine AI-Pause aussehen? Wie kann man tatsächlich die Schaffung einer superintelligenten KI verhindern?
---
Wenn wir die Schaffung einer superintelligenten KI zulassen, riskieren wir [jedes einzelne Leben auf der Erde](/xrisk).
Wenn wir über eine Pause sprechen, sprechen wir über die [Umsetzung eines internationalen Verbots der Schaffung einer superintelligenten KI](/proposal).
Einige argumentieren, dass es zu früh ist, die Pause-Taste zu drücken (wir [tun es nicht](/urgency)), aber die meisten Experten scheinen sich einig zu sein, dass es gut sein könnte, eine Pause einzulegen, wenn die Entwicklungen zu schnell voranschreiten.
Aber momentan _haben wir keine Pause-Taste_.
Also sollten wir anfangen, darüber nachzudenken, wie das funktionieren könnte und wie wir es umsetzen können.

## Das Rennen: warum wir internationale Zusammenarbeit benötigen {#the-race-why-we-need-international-cooperation}

Wir erwarten nicht, dass ein einzelnes Land in der Lage ist, eine Pause umzusetzen.
Die wirtschaftlichen Anreize sind zu stark, und die Verlangsamung der KI-Entwicklung würde ein Land in einen wirtschaftlichen und geopolitischen Nachteil bringen.
Die Kosten einer Unterinvestition in Sicherheit sind global verteilt, während die Vorteile einer Beschleunigung lokal sind.
Dieses spieltheoretische Problem wird manchmal als "Moloch" oder ein "Rennen nach unten" bezeichnet.

Der einzige Ausweg ist ein _internationales Abkommen_.
Deswegen sind wir so besessen von [Gipfeltreffen](/summit): diese sind die Veranstaltungen, bei denen globale Entscheidungsträger zusammenkommen und an einer globalen Lösung arbeiten.
Oder zumindest, das ist es, was wir wollen, dass sie tun.
Bisher haben alle KI-Sicherheitsgipfeltreffen nicht zu einer sinnvollen Regulierung geführt.
Es liegt an Ihnen und mir, [sie zu überzeugen](/action).

## Compute-Governance {#compute-governance}

Um ein modernes LLM (wie GPT-4) zu trainieren, benötigt man eine Menge hochspezialisierter und teurer Hardware.
GPT-4 wurde auf 25.000 Nvidia A100-GPUs trainiert, die jeweils 10.000 Dollar kosten.
Und viele erwarten, dass KI-Modelle in Zukunft noch größer werden.

Die schiere Skalierung moderner KI-Trainingsanforderungen ist immens.
Microsoft hat kürzlich einen Plan angekündigt, ein [Kernkraftwerk zu bauen](https://www.theverge.com/2024/9/20/24249770/microsoft-three-mile-island-nuclear-power-plant-deal-ai-data-centers), um seine KI-Strombedürfnisse zu decken.
Glücklicherweise für uns bedeutet dies, dass KI-Trainingsläufe schwer zu verstecken sind, zumindest in naher Zukunft.

Durch die Kontrolle und Überwachung der KI-Chip-Lieferkette können Regierungen oder andere Regulierungsbehörden sicherstellen, dass niemand einen gefährlichen KI-Trainingslauf startet.
Lassen Sie uns in die verschiedenen Engpässe in dieser Lieferkette eintauchen.

### Engpässe in der Chip-Lieferkette {#choke-points-in-the-chip-supply-chain}

Es ist schwer, die Komplexität und Interdependenz der KI-Chip-Lieferkette zu übertreiben.
Dies ist großartige Nachricht für die Regulierung.
Durch die Hardware können wir die Trainingsläufe regulieren.

#### ASML und SMEE - die Lithographie-Engpässe {#asml-and-smee---the-lithography-bottlenecks}

Alle modernen Chips werden mithilfe von Lithographiemaschinen hergestellt: riesigen Maschinen, die jeweils 200 Millionen Dollar kosten und Licht auf einen Siliziumwafer projizieren.
Dieser Lithographieprozess ist einer der komplexesten und teuersten Teile des Chip-Herstellungsprozesses.
Top-Tier-KI-Chips werden alle mithilfe von EUV-Lithographie hergestellt, und ASML ist das einzige Unternehmen, das diese Maschinen herstellt.
Dieses niederländische Unternehmen ist einer der wichtigsten potenziellen Engpässe für die KI-Regulierung.
Diese Maschinen sind unglaublich komplex und erfordern viel Expertise, um sie zu bauen und zu warten.
Bemerkenswerterweise haben sie [Fernabschaltungen](https://www.businessinsider.com/asml-tsmc-semiconductor-chip-equipment-kill-switch-china-invade-taiwan-2024-5) (hauptsächlich für den Fall, dass Taiwan angegriffen wird), also ist die Pause-Taste in gewisser Weise bereits eingebaut.

Die niederländische Regierung hat strenge Exportkontrollen für ihre EUV-Lithographiemaschinen eingerichtet, die Exportgenehmigungen erfordern.
Diese Exportkontrollen wurden hauptsächlich eingerichtet, um Chinas Chip-Ambitionen zu verlangsamen.
Die [USA, Japan und die Niederlande](https://apnews.com/article/technology-district-of-columbia-netherlands-china-business-6801d6c5f65b0bc1df6186e2e89a6f7d) haben ein (nicht öffentliches) Abkommen geschlossen, um Chip- und Lithographie-Exporte nach China zu beschränken.

Das chinesische Unternehmen SMEE versucht, aufzuholen, aber es ist nicht in der Lage, eigene EUV-Maschinen herzustellen.
Ihre DUV-Maschinen sind [immer noch bei 28nm](https://www.scmp.com/tech/big-tech/article/3278235/chinese-chip-making-shows-progress-new-euv-patent-domestic-lithography-champion) stecken, was Generationen hinter ASMLs 5nm-EUV-Prozess zurückliegt, geschweige denn ASMLs kommende 2nm-Maschinen.
Also ist SMEE nicht in der Lage, moderne KI-Chips herzustellen.

Mit anderen Worten: ASML ist ein grundlegender Engpass in der KI-Chip-Lieferkette.

#### TSMC, Samsung und SMIC - Die größten Fabs {#tsmc-samsung-amd-smic---the-largest-fabs}

Der Bau eines Fabs (einer Chip-Fabrik) ist erstaunlich schwierig: es hat null Toleranz für Staubpartikel, erfordert die teuersten High-Tech-Geräte und hat eine sehr komplexe Lieferkette.
Ein modernes Fab kostet etwa 10 bis 20 Milliarden Dollar, um herzustellen.

Die Taiwan Semiconductor Manufacturing Company produziert etwa 90% der modernen KI-Chips, die alle bei 7nm-Präzision oder besser hergestellt werden.
Samsung ist das einzige andere Fab, das moderne KI-Chips produzieren kann.

Aber das chinesische SMIC holt schnell auf - sie haben bereits einen funktionsfähigen 7nm-Prozess.
Aufgrund von US- und NL-Exportkontrollen kann SMIC keine ASML-EUV-Maschinen kaufen und ist jetzt auch bei der Anschaffung älterer DUV-Maschinen eingeschränkt.
Im Juni 2024 zeigte ein [Bericht](https://evertiq.com/news/55926), dass SMIC 5nm-Chips mithilfe von DUV-Hardware produzieren kann,
und jetzt in der Lage ist, 7nm-KI-Chips zu produzieren (etwa drei Jahre hinter dem 4nm-Prozess, den ASMLs EUV-Maschinen produzieren können), aber SMICs EUV-Lithographie ist von niedrigen Ausbeuten geplagt.

#### Zeiss - Spiegel und Linsen {#zeiss---mirrors--lensens}

ASMLs EUV-Maschinen verwenden Spiegel und Linsen von der deutschen Firma Zeiss.
Im Jahr 2016 kaufte ASML [25%](https://optics.org/news/7/11/11) von Zeiss, und die beiden Unternehmen haben eine sehr enge Beziehung.
Es ist wahrscheinlich, dass kein anderes Unternehmen in der Lage ist, diese Optiken herzustellen.

### Verifizierungsmethoden - Verhinderung großer Trainingsläufe {#verification-methods---preventing-large-training-runs}

Jetzt, da wir verschiedene Engpässe in der Chip-Lieferkette identifiziert haben, können wir anfangen, darüber nachzudenken, wie wir große Trainingsläufe verhindern können.
Diese oben genannten Akteure können unter Druck gesetzt werden (von Regierungen), um sicherzustellen, dass ihre Produkte nicht für gefährliche KI-Trainingsläufe verwendet werden.

Aber wie kann dies verifiziert werden?

Das Papier ["Verifizierungsmethoden für internationale KI-Abkommen"](https://arxiv.org/abs/2408.16074) listet verschiedene Optionen auf:

1. **Fernerkundung**: Verwendet Satelliten- und Infrarot-Bildgebung, um Rechenzentren durch visuelle und thermische Signaturen zu erkennen. Hochgradig machbar, aber begrenzt durch Tarnung oder unterirdische Anlagen.
2. **Whistleblower**: Verlässt sich auf Insider, die Nicht-Compliance melden, motiviert durch rechtliche und finanzielle Schutzmaßnahmen. Machbar, aber abhängig von Insider-Zugang und Bereitschaft zur Offenlegung.
3. **Energieüberwachung**: Verfolgt den Stromverbrauch, um große KI-Operationen zu identifizieren, machbar, wenn Muster eindeutig sind. Machbarkeit variiert; Daten können durch andere hochenergetische Aktivitäten verschleiert werden.
4. **Zoll-Daten-Analyse**: Überwacht den Import/Export von KI-Hardware auf Anomalien. Machbar, insbesondere für Importe, obwohl Länder mit inländischer Produktion möglicherweise nicht erkannt werden.
5. **Finanz-Intelligence**: Beobachtet große oder ungewöhnliche Transaktionen im Zusammenhang mit KI-Hardware-Käufen. Machbar, wenn Finanz-Privatsphäre und Bankgesetze es zulassen, oft am besten in Kombination mit anderen Methoden.
6. **Rechenzentrum-Inspektionen**: Physische Standort-Inspektionen, um die Einhaltung von Hardware-Grenzen und Sicherheitsprotokollen zu überprüfen. Effektiv, wenn das Gastland Inspektionen zulässt; invasiv und ressourcenintensiv.
7. **Halbleiter-Fertigungsanlagen-Inspektionen**: Überprüft die Einhaltung von Chip-Produktionsvorschriften durch Inspektionen von Anlagen mit relevanter Hardware. Machbar, aber erfordert erhebliche Ressourcen und die Zustimmung des Gastlandes.
8. **KI-Entwickler-Inspektionen**: Überprüft Einrichtungen auf autorisierten Code, Sicherheitsprotokolle und KI-Evaluierungsdaten. Effektiv, aber hochinvasiv, erfordert spezialisierte Expertise und die Kooperation des Landes.
9. **Chip-Ortung**: Verfolgt die Bewegung von KI-Chips, um deren Einsatz zu überwachen. Machbar mit internationalen Abkommen, aber umgehbar durch Deaktivierung der Ortung oder Spoofing von Standortdaten.
10. **Chip-basierte Berichterstattung**: Integriert Berichtsmechanismen in Chips, um zu warnen, wenn diese über autorisierte Grenzen hinaus verwendet werden. Machbar, aber herausfordernd, erfordert internationale Standards und Hardware-Entwicklung; umgehbar durch Modifikation der Firmware.

Jede Methode hat ihre Stärken und Schwächen, erfordert oft komplementäre Ansätze oder internationale Zusammenarbeit für eine effektive Umsetzung.

Andere vorgeschlagene Methoden umfassen:

1. **[FlexHEGs](https://yoshuabengio.org/wp-content/uploads/2024/09/FlexHEG-Interim-Report_2024.pdf)**: Eine neue Art von Chip, der programmiert werden kann, sich selbst zu zerstören, wenn bestimmte Bedingungen erfüllt sind.

Eine internationale Institution könnte eingerichtet werden, um diese Verifizierungsmethoden zu überwachen und die Pause durchzusetzen.

## Software-Governance {#software-governance}

Physische Chips sind unser primärer Fokus, aber wir möchten auch die _Software_ regulieren, die zum Trainieren und Ausführen von KI-Modellen verwendet wird.
Es ist durchaus möglich, dass die größten Rechencluster ausreichend Leistung haben, um ein katastrophal gefährliches Modell zu trainieren, aber ihnen immer noch die Software fehlt.
Lassen Sie uns in die Arten von Software-Innovationen eintauchen, die wir unterscheiden können.

### Software-Innovationen {#software-innovations}

Erstens gibt es _Trainings_-Innovationen.
Die Transformer-Architektur zum Beispiel ermöglichte es KI-Modellen, viel leistungsfähiger zu sein, bei viel geringeren Kosten.
Das auf Transformer basierende ALBERT-Modell [übertraf](https://arxiv.org/pdf/2308.04950) das BERT-Modell, obwohl es aus 18-mal weniger Parametern bestand.
In Zukunft könnten wir noch effizientere Architekturen sehen.
Es gibt auch Innovationen bei den Daten, die einem Modell zugeführt werden.

Zusätzlich zu Trainingsverbesserungen haben wir verschiedene _Laufzeit_-Verbesserungen gesehen.
Chain-of-Thought, Graph-of-Thought und andere Techniken können drastische Verbesserungen in der Leistung von KI-Modellen bringen.
Tools wie AutoGPT können einfache Chatbots in vollständig autonome Agenten verwandeln, die das Web durchsuchen, E-Mails senden und andere Aufgaben ausführen.
OpenAIs o1-Modell ermöglicht größere Denkfähigkeiten, indem es dem Modell erlaubt, mehr Zeit damit zu verbringen, eine Antwort zu überdenken, bevor es sie liefert.

### Regulierung von Software {#regulating-software}

Die Software-Seite von KI ist schwieriger zu kontrollieren als die Hardware-Seite.
Software ist nur Information - sie kann leicht kopiert und verteilt werden.
Dennoch haben wir Informationen zuvor verboten.
Kinderpornografie zum Beispiel ist illegal zu produzieren, zu verbreiten und zu besitzen.
Die gleichen Durchsetzungsmechanismen könnten verwendet werden, um gefährliche KI-Software zu regulieren.