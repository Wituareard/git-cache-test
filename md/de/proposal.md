

---
title: PauseAI-Vorschlag
description: Einführung einer vorübergehenden Pause bei der Entwicklung von KI-Systemen, die leistungsfähiger sind als GPT-4, Verbot der Schulung auf urheberrechtlich geschütztem Material, Haftung der Modellersteller.
---
**Einführung einer Pause bei der Entwicklung von KI-Systemen, die leistungsfähiger sind als GPT-4**, bis wir wissen, wie wir sie sicher bauen und demokratisch kontrollieren können.

_Version: 25. November 2024_

Einzelne Länder können und sollten diese Maßnahme _sofort_ umsetzen.
Insbesondere die USA (oder Kalifornien) sollten eine Pause einlegen, da sie Heimat fast aller führenden KI-Unternehmen sind.
Viele Wissenschaftler und Branchenführer [stimmen darin überein, dass eine Pause notwendig ist](https://futureoflife.org/open-letter/pause-giant-ai-experiments/), und die (US-amerikanische) Öffentlichkeit unterstützt eine Pause ebenfalls stark ([64%](https://www.campaignforaisafety.org/usa-ai-x-risk-perception-tracker/) - [69%](https://today.yougov.com/topics/technology/survey-results/daily/2023/04/03/ad825/2)).

Allerdings können wir nicht erwarten, dass Länder oder Unternehmen ihre Wettbewerbsvorteile riskieren, indem sie KI-Schulungen für längere Zeit pausieren, wenn andere Länder oder Unternehmen dies nicht auch tun.
Deshalb benötigen wir eine **globale Pause**.

Lassen Sie uns nun sehen, was notwendig ist, um dorthin zu gelangen.

## Auf dem Weg zu einem Vertrag {#getting-to-a-treaty}

Ein internationales Abkommen wird typischerweise durch einen Gipfel etabliert, auf dem die Führer der Länder zusammenkommen, um das Thema zu diskutieren und eine Entscheidung zu treffen.
Wir hatten bereits [drei KI-Sicherheitsgipfel](/summit).

Das primäre Endziel dieser Gipfel sollte ein **Vertrag** sein.
Bisher waren die Gipfel jedoch nicht effektiv darin, etwas rechtlich Bindendes zu produzieren.
Und der Vertragsaufbau neigt dazu, langsam und anfällig für Vetos zu sein.
Wir [haben möglicherweise nicht die Zeit](/urgency), auf traditionelle Vertragsverhandlungsprozesse zu warten.

Deshalb benötigen wir einen neuen **Vertragsverhandlungsprozess**:

- Die Beteiligung sowohl der **USA als auch Chinas** ist entscheidend.
- Er muss **unempfindlich gegen Vetos** durch ein einzelnes Land sein.
- Er muss **schnell** sein. Normale Vertragsverhandlungsprozesse dauern Jahre, und wir [haben möglicherweise nicht diese Zeit](/urgency).
- Der Umfang dieses Vertragsverhandlungsprozesses ist beispiellos, und er benötigt die Zustimmung aller Länder.

Der Vertrag selbst sollte die folgenden **Maßnahmen** enthalten:

### Vertragsmaßnahmen {#treaty-measures}

- **Einrichtung einer internationalen KI-Sicherheitsbehörde**, ähnlich der IAEO. Diese Behörde wird für Folgendes verantwortlich sein:
  - Erteilung von Genehmigungen für _Einsätze_. Dies umfasst Red-Teaming-/Modellevaluierungen.
  - Erteilung von Genehmigungen für _neue Schulungen_ von KI-Modellen oberhalb einer bestimmten Größe (z. B. 1 Milliarde Parameter).
  - Regelmäßige Treffen, um den Fortschritt der KI-Sicherheitsforschung zu diskutieren.
- **Nur die Schulung von allgemeinen KI-Systemen, die leistungsfähiger sind als GPT-4, erlauben, wenn ihre Sicherheit garantiert werden kann**.
  - Mit leistungsfähiger als GPT-4 meinen wir alle KI-Modelle, die entweder 1) größer als 10^12 Parameter sind, 2) mehr als 10^25 FLOPs für die Schulung verwenden oder 3) Fähigkeiten haben, die GPT-4 überschreiten. Beachten Sie, dass dies nicht auf _spezialisierte_ KI-Systeme abzielt, wie z. B. Bilderkennung für die Krebsdiagnose.
  - Es ist möglich, dass das KI-Alignmentsproblem _nie gelöst wird_ - es könnte unlösbar sein. In diesem Fall sollten wir die Schulung solcher Systeme nie erlauben.
  - **Überprüfen**, dass diese gefährlichen Schulungen nicht stattfinden. Dies kann auf [zahlreiche Weise](https://arxiv.org/abs/2408.16074) erfolgen: [GPU-Tracking](https://arxiv.org/abs/2303.11341), Anreize für Whistleblower, Energieüberwachung, Inspektionen von Rechenzentren, Finanzanalyse, Inspektionen von Halbleiterherstellungsanlagen, Inspektionen von KI-Entwicklern, Chip-Ortung und chipbasierte Berichterstattung. Die [KI-Chip-Lieferkette](https://www.governance.ai/post/computing-power-and-the-governance-of-ai) ist stark zentralisiert, was eine globale Überwachung ermöglicht.
  - Erfordernis einer [Überwachung während der Schulungen](https://www.alignmentforum.org/posts/Zfk6faYvcf5Ht7xDx/compute-thresholds-proposed-rules-to-mitigate-risk-of-a-lab).
  - Selbst wenn wir kontrollierbare, sichere KI bauen können, sollten wir eine solche Technologie nur mit **starker demokratischer Kontrolle** bauen und einsetzen. Eine Superintelligenz ist zu mächtig, um von einem einzelnen Unternehmen oder Land kontrolliert zu werden.
- **Nur den Einsatz von Modellen erlauben, nachdem keine [gefährlichen Fähigkeiten](/dangerous-capabilities) vorhanden sind**. (Vor-Einsatz-Evaluierung)
  - Wir benötigen Standards und unabhängige Red-Teaming-Evaluierungen, um zu bestimmen, ob ein Modell gefährliche Fähigkeiten hat.
  - Die Liste der gefährlichen Fähigkeiten kann sich im Laufe der Zeit ändern, wenn die KI-Fähigkeiten wachsen.
  - Beachten Sie, dass die ausschließliche Verwendung von Modellevaluierungen [nicht ausreichend ist](/4-levels-of-ai-regulation).

Die Einführung einer Pause _kann_ nach hinten losgehen, wenn sie nicht ordnungsgemäß durchgeführt wird.
Lesen Sie mehr darüber, [wie diese Risiken minimiert werden können](/mitigating-pause-failures).

Für weitere Details darüber, wie die KI-Chip-Lieferkette für eine globale Überwachung genutzt werden kann, lesen Sie [Building the Pause Button](/building-the-pause-button).

## Weitere Maßnahmen, die den Fortschritt effektiv verlangsamen {#other-measures-that-effectively-slow-down}

- **Verbot der Schulung von KI-Systemen auf urheberrechtlich geschütztem Material**. Dies hilft bei Urheberrechtsproblemen, verlangsamt die wachsende Ungleichheit und verlangsamt den Fortschritt in Richtung Superintelligenz.
- **Haftung der KI-Modellersteller** für kriminelle Handlungen, die unter Verwendung ihrer KI-Systeme begangen werden. Dies gibt den Modellerstellern mehr Anreize, sicherzustellen, dass ihre Modelle sicher sind.

## Langfristige Politik {#long-term-policy}

Zum Zeitpunkt des Schreibens kostet die Schulung eines GPT-3-Modells Millionen von Dollar.
Dies macht es sehr schwierig, solche Modelle zu trainieren, und erleichtert die Kontrolle der Schulung durch GPU-Tracking.
Allerdings sinken die Kosten für die Schulung eines Modells aufgrund von Hardwareverbesserungen und neuen Trainingsalgorithmen exponentiell.

Es wird einen Punkt geben, an dem potenziell superintelligente KI-Modelle für einige Tausend Dollar oder weniger trainiert werden können, vielleicht sogar auf Consumer-Hardware.
Wir müssen darauf vorbereitet sein.
Wir sollten die folgenden Politiken in Betracht ziehen:

- **Begrenzung der Veröffentlichung von Trainingsalgorithmen / Laufzeitverbesserungen**. Manchmal wird ein neuer Algorithmus veröffentlicht, der die Schulung viel effizienter macht. Die Transformer-Architektur ermöglichte beispielsweise nahezu alle jüngsten Fortschritte in der KI. Diese Art von Fähigkeitssteigerungen kann jederzeit auftreten, und wir sollten die Veröffentlichung solcher Algorithmen begrenzen, um das Risiko eines plötzlichen Fähigkeitszuwachses zu minimieren. Es gibt auch Innovationen, die [dezentralisierte Schulungen](https://www.primeintellect.ai/blog/opendiloco) ermöglichen. Ebenso könnten einige Laufzeitinnovationen drastisch ändern, was mit bestehenden Modellen möglich ist. Ein Verbot der Veröffentlichung solcher Algorithmen kann durch ähnliche Mittel wie das Verbot anderer Formen von Informationen, wie z. B. illegale pornografische Medien, umgesetzt werden.
- **Begrenzung der Fähigkeitssteigerungen von Rechenressourcen**. Wenn die Schulung einer Superintelligenz auf Consumer-Hardware möglich wird, sind wir in Schwierigkeiten. Wir sollten die Fähigkeitssteigerungen von Hardware (z. B. durch Beschränkungen der Lithografie, Chip-Design und neuartige Rechenparadigmen wie photonische Chips und Quantencomputing) begrenzen.

## Helfen Sie, dies zu erreichen {#help-to-achieve-this}

[Treten Sie](/join) der Bewegung bei, um zusammenzuarbeiten oder [ergreifen Sie Maßnahmen](/action) auf eigene Faust!