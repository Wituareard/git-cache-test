

---
title: 4 Ebenen der KI-Sicherheitsregulierung
description: Ein Rahmenwerk zum Nachdenken darüber, wie die Risiken durch leistungsfähige KI-Systeme gemildert werden können
image: /4levels.png
---

Mit zunehmenden KI-Fähigkeiten steigen auch die Risiken, die diese Systeme für die Menschheit darstellen.
Viele Wissenschaftler haben bereits vor dem Risiko des menschlichen Aussterbens gewarnt.

In diesem Artikel werden wir unser 4-Ebenen-Rahmenwerk für die Regulierung der KI-Sicherheit vorstellen.

## KI-Pipeline als Rahmenwerk für die Sicherheitsgovernance {#ai-pipeline-as-a-framework-for-safety-governance}

Die KI-Erstellungspipeline besteht aus verschiedenen Schritten, die jeweils auf unterschiedliche Weise reguliert werden können.
Diese Pipeline besteht aus:

- **Hardware und Algorithmen**, die für das Training von KI-Modellen verwendet werden
- **Trainingsläufe**, bei denen die Hardware und Algorithmen verwendet werden, um ein Modell zu erstellen
- **Bereitstellung**, bei der das trainierte Modell der Öffentlichkeit zugänglich gemacht wird
- **Nutzung**, bei der das bereitgestellte Modell von Einzelpersonen und Unternehmen genutzt wird

Je später in der Pipeline wir regulieren, desto höher sind die Risiken, denen wir ausgesetzt sind.
Wenn wir ein hohes Maß an Sicherheit erreichen wollen, müssen wir früher in der Pipeline regulieren.
Deshalb gehen wir, wenn wir die 4 Ebenen der KI-Regulierung durchlaufen, die KI-Erstellungspipeline rückwärts.

![4 Ebenen der KI-Sicherheitsregulierung](/4levels.png)

## Ebene 1: Regulierung der Nutzung {#level-1-regulate-usage}

Beispiele:

- **Verbot von autonomen Agenten-Laufzeiten** (wie AutoGPT)
- **Verbot von gefährlichen Anweisungen**

Diese Maßnahmen zielen darauf ab, zu verhindern, dass Benutzer gefährliche oder schädliche Aktionen mit KI-Modellen durchführen.
Auf dieser Ebene liegt die Verantwortung bei den Benutzern der Modelle, nicht bei den Erstellern.
Wir sind darauf angewiesen, dass alle (potenziell Millionen) Benutzer die Regulierungen einhalten.
Dies bietet nur ein sehr geringes Maß an Schutz gegen KI-Gefahren.

## Ebene 2: Regulierung der Bereitstellung {#level-2-regulate-deployment}

Beispiele:

- **Anforderungen an Red-Teaming**. Dies bedeutet, dass ein KI-Modell vor seiner Bereitstellung von einem Red-Team getestet wird, um zu sehen, ob es gehackt (jailbroken) oder missbraucht werden kann.
- **Verbot der Bereitstellung und Open-Sourcing** von Modellen mit [gefährlichen Fähigkeiten](/dangerous-capabilities).

Wenn wir die Bereitstellung regulieren, verhindern wir, dass gefährliche Modelle verfügbar sind.
Dies bedeutet, dass die Verantwortung bei den Erstellern der Modelle liegt.
Dies ist eine sicherere Situation als Ebene 1, da wir nun auf eine viel kleinere Gruppe von Menschen angewiesen sind, verantwortungsvoll zu handeln.

Allerdings lassen wir immer noch gefährliche Trainingsläufe zu, so dass Unfälle in KI-Labors (einschließlich des Lecks von gefährlichen KI-Modellen oder der Erstellung von Rogue-KI) immer noch passieren können.

## Ebene 3: Regulierung der Trainingsläufe {#level-3-regulate-training-runs}

Beispiele:

- **Sicherheitsnachweis** vor der Genehmigung zum Training eines bestimmten Modells. Dies kann auch einen formalen Nachweis der Ausrichtung umfassen. [Dieser Beitrag beschreibt einige der aktuellen Sicherheitsprobleme](https://www.lesswrong.com/posts/mnoc3cKY3gXMrTybs/a-list-of-core-ai-safety-problems-and-how-i-hope-to-solve).
- Festlegung einer **Skalierungsobergrenze für das Training neuer Modelle** (z.B. eine maximale Anzahl von FLOPS). Dies könnte auch den Prozess des Fine-Tunings umfassen.
- **Lizenzierung** zum Training von KI-Modellen (oberhalb einer bestimmten Größe / mit bestimmten Fähigkeiten).
- **Verbot des Trainings auf gefährlichen Datentypen**. Einige Arten von Trainingsdaten können zu [gefährlichen Fähigkeiten](/dangerous-capabilities) führen, wie z.B. Hacking oder die Erstellung von Biowaffen. Wir könnten das Training auf Daten verbieten, die dieses Wissen enthalten.
- **Verbot des Trainings auf urheberrechtlich geschützten Daten**. Dies zielt nicht direkt auf unsichere Daten ab, aber es limitiert die Menge an Daten, die verwendet werden können, was uns Zeit gibt, herauszufinden, wie wir sichere KI-Modelle bauen können.

Wenn wir die Trainingsläufe regulieren, verhindern wir, dass gefährliche Modelle überhaupt erstellt werden.
Dies wird Unfälle in KI-Labors, die sich an die Regulierungen halten, verhindern.

Allerdings lassen wir immer noch die Verteilung von Hardware und Algorithmen zu, die für das Training gefährlicher Modelle verwendet werden können, so dass wir immer noch auf die Ersteller dieser Modelle angewiesen sind, verantwortungsvoll zu handeln.

## Ebene 4: Regulierung von Hardware und Algorithmen {#level-4-regulate-hardware--algorithms}

Beispiele:

- **Begrenzung der Verteilung von Trainingshardware**. Spezialisierte Hardware für das Training von KI-Modellen wird schnell zum wichtigsten Produkt von Chip-Herstellern. Die Lieferkette für diese Hardware ist sehr zentralisiert, und die Hardware ist sehr teuer. Dies bedeutet, dass es [relativ einfach ist, die Verteilung dieser Hardware zu regulieren](https://arxiv.org/abs/2303.11341).
- **Verbot der Veröffentlichung neuer Trainingsarchitekturen**. Neue KI-Trainingsarchitekturen können zu dramatischen Fähigkeitssteigerungen führen. Das Transformer-Modell ermöglichte beispielsweise nahezu alle jüngsten Fortschritte in der KI. Wir könnten die Veröffentlichung solcher Architekturen limitieren, um plötzliche Fähigkeitssteigerungen zu verhindern.

Wenn wir auch Hardware und Algorithmen regulieren, machen wir es nicht nur illegal, sondern auch sehr schwierig, gefährliche Modelle zu trainieren.
Dies bietet uns den besten Schutz gegen die Risiken durch KI.

## Einschränkungen {#limitations}

Hinweis: Dieses Rahmenwerk ist nicht perfekt, und nicht alle möglichen Arten von KI-Regulierungen passen sauber in eine der genannten Ebenen.
Beispielsweise kann die rechtliche Haftung für Modellersteller als Ebene-1-"Nutzung"-Typ-Regulierung eingestuft werden, da sie nach der Bereitstellung durchgesetzt wird, aber sie könnte auch als Ebene-2- oder Ebene-3-Typ-Regulierung eingestuft werden, da sie den Erstellern helfen kann, zu überlegen, ob ein bestimmtes Modell bereitgestellt oder trainiert werden sollte.

## Schlussfolgerungen {#conclusions}

In diesem Artikel haben wir unser 4-Ebenen-Rahmenwerk für die Regulierung der KI-Sicherheit vorgestellt.
Mit diesem Modell können wir leichter über die Wirksamkeit von KI-Regulierungen auf verschiedenen Stufen der KI-Erstellungspipeline nachdenken.
Wir können auch sehen, dass die ersten beiden Ebenen nicht viel Schutz gegen die (existenziellen) Risiken durch KI bieten.
Das Verhindern gefährlicher Trainingsläufe und die Regulierung von Hardware und Algorithmen sind weit zuverlässigere Wege, um Sicherheit zu gewährleisten.