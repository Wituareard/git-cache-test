

---
title: PauseAI-Vorschlag
description: Einführung einer vorübergehenden Pause bei der Entwicklung von KI-Systemen, die leistungsfähiger sind als GPT-4, Verbot der Schulung auf urheberrechtlich geschütztem Material, Haftung der Modellersteller.
---
**Einführung einer Pause bei der Entwicklung von KI-Systemen, die leistungsfähiger sind als GPT-4**, bis wir wissen, wie wir sie sicher bauen und unter demokratischer Kontrolle halten können.

_Version: 9. Oktober 2024_
Einzelne Länder können und sollten diese Maßnahme _sofort_ umsetzen.
Insbesondere die USA (oder Kalifornien im Speziellen) sollten eine Pause einlegen, da sie Heimat fast aller führenden KI-Unternehmen sind.
Viele Wissenschaftler und Branchenführer [stimmen darin überein, dass eine Pause notwendig ist](https://futureoflife.org/open-letter/pause-giant-ai-experiments/), und die (US-amerikanische) Öffentlichkeit unterstützt eine Pause auch stark ([64%](https://www.campaignforaisafety.org/usa-ai-x-risk-perception-tracker/) - [69%](https://today.yougov.com/topics/technology/survey-results/daily/2023/04/03/ad825/2)).

Allerdings können wir nicht erwarten, dass Länder oder Unternehmen ihre Wettbewerbsvorteile riskieren, indem sie KI-Schulungen für längere Zeit pausieren, wenn andere Länder oder Unternehmen dies nicht auch tun.
Deshalb benötigen wir eine **globale Pause**.

## Umsetzung einer globalen Pause {#implementing-a-global-pause}

Ein internationales Abkommen wird typischerweise durch einen Gipfel geschaffen, auf dem die Führer der Länder zusammenkommen, um das Thema zu diskutieren und eine Entscheidung zu treffen.
Das Vereinigte Königreich hat sich bemüht und im Herbst 2023 einen KI-Sicherheitsgipfel ausgerichtet.
Und zwei weitere Gipfel wurden angekündigt.
[Mehr über die Gipfel](/summit).

Das Hauptziel des Gipfels sollte ein **Vertrag** sein.
Dieser Vertrag sollte die politischen Maßnahmen festlegen, die uns vor den [Risiken der KI](/risks) schützen.
Dieser Vertrag muss von allen UN-Mitgliedsstaaten unterzeichnet werden.

- **Einrichtung einer internationalen KI-Sicherheitsbehörde**, ähnlich der IAEO. Diese Behörde wird verantwortlich sein für:
  - Die Genehmigung von _Einsätzen_. Dies wird auch Red-Teaming-/Modellevaluierungen umfassen.
  - Die Genehmigung von _neuen Schulungen_ von KI-Modellen oberhalb einer bestimmten Größe (z.B. 1 Milliarde Parameter).
  - Regelmäßige Treffen, um den Fortschritt der KI-Sicherheitsforschung zu diskutieren.
- **Nur die Schulung von allgemeinen KI-Systemen, die leistungsfähiger sind als GPT-4, erlauben, wenn ihre Sicherheit garantiert werden kann**.
  - Mit leistungsfähiger als GPT-4 meinen wir alle KI-Modelle, die entweder 1) größer als 10^12 Parameter sind, 2) mehr als 10^25 FLOPs für die Schulung verwenden oder 3) Fähigkeiten haben, die GPT-4 überschreiten.
  - **Überprüfen**, dass diese gefährlichen Schulungen nicht stattfinden. Dies kann auf [zahlreiche Weise](https://arxiv.org/abs/2408.16074) erfolgen: [GPU-Tracking](https://arxiv.org/abs/2303.11341), Anreize für Whistleblower, Energieüberwachung, Inspektionen von Rechenzentren, Finanzanalyse, Inspektionen von Halbleiterherstellungsanlagen, Inspektionen von KI-Entwicklern, Chip-Ortung und chipbasierte Berichterstattung. Die [KI-Chip-Lieferkette](https://www.governance.ai/post/computing-power-and-the-governance-of-ai) ist stark zentralisiert, was eine globale Überwachung ermöglicht.
  - Beachten Sie, dass dies nicht auf _spezialisierte_ KI-Systeme abzielt, wie z.B. Bilderkennung für die Krebsdiagnose.
  - Erfordern Sie [Überwachung während der Schulungen](https://www.alignmentforum.org/posts/Zfk6faYvcf5Ht7xDx/compute-thresholds-proposed-rules-to-mitigate-risk-of-a-lab).
  - Es ist möglich, dass das KI-Alignment-Problem _nie gelöst wird_ - es könnte unlösbar sein. In diesem Fall sollten wir niemals die Schulung solcher Systeme zulassen.
  - Selbst wenn wir kontrollierbare, sichere KI bauen können, sollten wir eine solche Technologie nur mit **starker demokratischer Kontrolle** bauen und einsetzen. Eine Superintelligenz ist zu mächtig, um von einem einzelnen Unternehmen oder Land kontrolliert zu werden.
- **Nur den Einsatz von Modellen nachdem keine [gefährlichen Fähigkeiten](/dangerous-capabilities) vorhanden sind, erlauben**.
  - Wir werden Standards und unabhängige Red-Teaming-Evaluierungen benötigen, um zu bestimmen, ob ein Modell gefährliche Fähigkeiten hat.
  - Die Liste der gefährlichen Fähigkeiten kann sich im Laufe der Zeit ändern, wenn die KI-Fähigkeiten wachsen.
  - Beachten Sie, dass die vollständige Abhängigkeit von Modellevaluierungen [nicht ausreichend ist](/4-levels-of-ai-regulation).

Die Umsetzung einer Pause _kann_ nach hinten losgehen, wenn sie nicht richtig durchgeführt wird.
Lesen Sie mehr über [wie diese Risiken minimiert werden können](/mitigating-pause-failures).

## Weitere Maßnahmen, die den Fortschritt effektiv verlangsamen {#other-measures-that-effectively-slow-down}

- **Verbot der Schulung von KI-Systemen auf urheberrechtlich geschütztem Material**. Dies hilft bei Urheberrechtsproblemen, verlangsamt die wachsende Ungleichheit und verlangsamt den Fortschritt in Richtung Superintelligenz.
- **Haftung der Modellersteller** für kriminelle Handlungen, die mit ihren KI-Systemen begangen werden. Dies gibt den Modellerstellern mehr Anreize, sicherzustellen, dass ihre Modelle sicher sind.

## Langfristige Politik {#long-term-policy}

Zum Zeitpunkt des Schreibens kostet die Schulung eines GPT-3-Modells Millionen von Dollar.
Dies macht es sehr schwierig, solche Modelle zu trainieren, und dies macht es einfacher, die Kontrolle der Schulung mithilfe von GPU-Tracking durchzusetzen.
Allerdings sinken die Kosten für die Schulung eines Modells aufgrund von Hardware-Verbesserungen und neuen Trainingsalgorithmen exponentiell.

Es wird einen Punkt geben, an dem potenziell superintelligente KI-Modelle für einige Tausend Dollar oder weniger trainiert werden können, vielleicht sogar auf Consumer-Hardware.
Wir müssen darauf vorbereitet sein.
Wir sollten die folgenden Politiken in Betracht ziehen:

- **Begrenzung der Veröffentlichung von Trainingsalgorithmen / Laufzeitverbesserungen**. Manchmal wird ein neuer Algorithmus veröffentlicht, der die Schulung viel effizienter macht. Die Transformer-Architektur ermöglichte beispielsweise nahezu alle jüngsten Fortschritte in der KI. Diese Art von Fähigkeits-Sprüngen kann jederzeit passieren, und wir sollten die Veröffentlichung solcher Algorithmen begrenzen, um das Risiko eines plötzlichen Fähigkeits-Sprungs zu minimieren. Es gibt auch Innovationen, die [dezentralisierte Schulungen](https://www.primeintellect.ai/blog/opendiloco) ermöglichen. Ebenso könnten einige Laufzeitinnovationen drastisch ändern, was mit bestehenden Modellen möglich ist. Das Verbot der Veröffentlichung solcher Algorithmen kann mithilfe ähnlicher Mittel umgesetzt werden, wie wir andere Formen von Informationen verbieten, wie z.B. illegale pornografische Medien.
- **Begrenzung der Fähigkeits-Fortschritte von Rechenressourcen**. Wenn die Schulung einer Superintelligenz auf Consumer-Hardware möglich wird, sind wir in Schwierigkeiten. Wir sollten die Fähigkeits-Fortschritte von Hardware begrenzen (z.B. durch Beschränkungen der Lithografie, Chip-Design und neuartige Rechenparadigmen wie photonische Chips und Quantencomputing).

## Helfen Sie, dies zu erreichen {#help-to-achieve-this}

[Treten Sie](/join) der Bewegung bei, um zusammenzuarbeiten oder [nehmen Sie selbst Maßnahmen](/action)!