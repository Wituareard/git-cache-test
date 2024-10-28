

---
title: Regulierung gefährlicher Fähigkeiten in der KI
description: Je leistungsfähiger KI in bestimmten Bereichen wird, desto größer werden die Risiken. Wie können wir verhindern, dass diese gefährlichen Fähigkeiten entstehen oder sich verbreiten?
---

In diesem Artikel werden wir diskutieren:

- Welche KI-Fähigkeiten gefährlich sein können
- Wie wir verhindern können, dass diese Fähigkeiten entstehen oder sich verbreiten
- Warum es gefährlich ist, sich auf Bewertungen als politische Maßnahme zu verlassen

Je leistungsfähiger KI-Modelle werden, desto gefährlicher werden sie auch.
Wo sollten wir also vorsichtig sein?
Ein bestimmter Schwellenwert, der oft erwähnt wird, ist AGI - oder künstliche allgemeine Intelligenz.
Es gibt viel Diskussion darüber, was AGI genau bedeutet.
Einige sagen, es ist, wenn KI alle kognitiven Aufgaben erledigen kann, die Menschen können.
Einige sagen, GPT-4 sei bereits AGI.
Steve Wozniak definiert AGI als das erste System, das in eine Küche eintreten und einen Kaffee kochen kann.

Aus Sicherheitssicht ist die Definition von AGI nicht so wichtig.
Tatsächlich kann sie uns ein falsches Gefühl von Sicherheit geben, weil wir denken könnten, wir seien sicher, bis wir AGI erreichen.
Selbst wenn eine KI keinen Kaffee kochen kann, kann sie immer noch gefährlich sein.
Was zählt, sind die Fähigkeiten, die eine KI hat.

In diesem Artikel werden wir uns mit verschiedenen gefährlichen Fähigkeiten befassen und was wir tun können, um zu verhindern, dass sie uns schaden.

## Welche Fähigkeiten können gefährlich sein? {#welche-fähigkeiten-können-gefährlich-sein}

- **Cybersicherheit**. Wenn eine KI in der Lage ist, Sicherheitslücken zu entdecken (insbesondere neue, unbekannte), kann sie (verwendet werden, um) [in Systeme einzudringen](/cybersecurity-risks). Aktuelle [State-of-the-Art](/sota)-KI-Systeme können einige Sicherheitslücken finden, aber noch nicht auf gefährlichem, fortgeschrittenem Niveau. Allerdings steigt mit zunehmenden Cybersicherheitsfähigkeiten auch das potenzielle Schadenspotential, das eine KI-gestützte Cyberwaffe anrichten könnte. Groß angelegte Cyberangriffe könnten unsere Infrastruktur stören, Zahlungen lahmlegen und Chaos verursachen.
- **Biologisch**. Entwurf neuer biologischer Agenzien oder Hilfe bei der Entwicklung einer Pandemie. Eine Gruppe von Studenten konnte einen Chatbot verwenden, um [alle Schritte zu erstellen, die benötigt werden, um eine neue Pandemie zu schaffen](https://arxiv.org/abs/2306.03809). Eine KI, die entwickelt wurde, um sichere Medikamente zu finden, wurde verwendet, um [40.000 neue chemische Waffen in sechs Stunden zu entdecken](https://www.theverge.com/2022/3/17/22983197/ai-new-possible-chemical-weapons-generative-models-vx).
- **Algorithmische Verbesserungen**. Eine KI, die effiziente Algorithmen für ein bestimmtes Problem finden kann, könnte zu einer rekursiven Schleife der Selbstverbesserung führen, die schnell außer Kontrolle gerät. Dies wird als _Intelligenzexplosion_ bezeichnet. Die resultierende KI wäre unglaublich leistungsfähig und könnte alle möglichen anderen gefährlichen Fähigkeiten haben. Glücklicherweise kann noch keine KI sich selbst verbessern. Allerdings gibt es KIs, die neue, sehr effiziente Algorithmen finden können (wie [AlphaDev](https://www.deepmind.com/blog/alphadev-discovers-faster-sorting-algorithms)).
- **Täuschung**. Die Fähigkeit, Menschen zu manipulieren, einschließlich sozialer Manipulation. Verschiedene Formen der Täuschung sind [bereits vorhanden](https://twitter.com/DanHendrycks/status/1699437800301752332) in aktuellen KI-Systemen. Zum Beispiel wurde Metas CICERO-KI (die entwickelt wurde, um zu "besserer, natürlicher KI-Mensch-Kooperation" zu führen) zu einem Expertenlügner, der andere Agenten im Spiel täuschte. Eine KI, die Menschen täuschen kann, kann Menschen während des Trainings täuschen. Sie könnte ihre Fähigkeiten oder Absichten verbergen.
- **Selbstreplikation**. Wenn eine KI neue Instanzen auf anderen Maschinen erstellen kann, besteht das Risiko, dass sie sich unkontrolliert verbreitet und zu einem [_KI-Übernahme_](/ai-takeover) führt. Eine hinreichend fähige KI könnte Menschen überlegen sein und zu [menschlichem Aussterben](/xrisk) führen. Beachten Sie, dass dies sogar passieren kann, bevor ein KI-Modell eingesetzt wird.

Diese Liste ist nicht erschöpfend, es gibt also andere gefährliche Fähigkeiten, die eine KI haben könnte.

## Verhinderung der Entstehung gefährlicher Fähigkeiten {#verhinderung-der-entstehung-gefährlicher-fähigkeiten}

Können wir verhindern, dass diese gefährlichen Fähigkeiten entstehen?
Wenn KIs größer werden und auf mehr Daten trainiert werden, erlangen sie neue Fähigkeiten.
Es stellt sich heraus, dass es sehr schwierig ist, vorherzusagen, welche Fähigkeiten entstehen werden und wie gut eine KI performen wird.
Deshalb werden sie oft als _Emergente Fähigkeiten_ bezeichnet.

Unser aktuelles Paradigma von großen Sprachmodellen ist fast inhärent unvorhersehbar.
KI-Modelle werden nicht wie Software geschrieben - sie werden trainiert.
Sie sind Black-Box-Systeme, die aus Milliarden von numerischen Parametern bestehen.
Niemand weiß wirklich, was darin vor sich geht.
Diese Unvorhersehbarkeit macht es schwierig zu sagen, ob ein Trainingslauf zu einer gefährlichen KI führen wird.
Interpretierbarkeitsforschung kann dies in Zukunft ändern, aber momentan können wir nicht wirklich erklären, warum KI tut, was sie tut.

Die Verhinderung der Entstehung gefährlicher Fähigkeiten kann praktisch nur auf eine Weise erfolgen:
Baue keine immer leistungsfähigeren KI-Systeme.
Dies wäre der sicherste Weg, aber das ist nicht, was KI-Labore vorschlagen.

## Fähigkeiten können nach dem Training hinzugefügt werden {#fähigkeiten-können-nach-dem-training-hinzugefügt-werden}

### Feinabstimmung {#feinabstimmung}

Feinabstimmung kann verwendet werden, um die Fähigkeiten eines bestehenden KI-Modells zu verbessern.
Dies ist ähnlich wie Training, aber es ist viel schneller, viel billiger, erfordert nicht so viel Daten und kann oft auf Consumer-Hardware durchgeführt werden.
Feinabstimmung ändert die KI-Parameter und ändert somit ihre Fähigkeiten.
Jetzt ist Feinabstimmung nicht so leistungsfähig wie ein vollständiger Trainingslauf, aber es kann immer noch bestehende Fähigkeiten verbessern.

### Jailbreaking {#jailbreaking}

Die größten KIs werden auf absolut riesigen Datenmengen trainiert.
Die meisten Bücher, wissenschaftlichen Artikel und Websites im Internet.
Es gibt viel hässliches Zeug in diesen Datensätzen.
KIs werden oft mit einer Technik namens RLHF (Reinforcement Learning from Human Feedback) feinabgestimmt, um sie hilfreich und nett zu machen.
In diesem Prozess muss die KI lernen, bestimmte Dinge nicht zu sagen, wie rassistische Bemerkungen, Erklärungen, wie man eine Bombe baut oder wie man eine neue Biowaffe erstellt.

Aber diese Sicherheitsvorkehrungen sind nicht perfekt.
So genanntes "Jailbreaking" ist eine Technik, bei der man versucht, die KI dazu zu bringen, diese Sicherheitsvorkehrungen zu ignorieren.
Dies kann durch [Anhängen bestimmter Wörter oder Zeichen an die Chat-Nachricht](https://twitter.com/AIPanicLive/status/1678942758872989696) oder durch [kreative Umformulierung der Nachricht](https://twitter.com/_annieversary/status/1647865782741749760) erfolgen.
Es ist [unklar](https://llm-attacks.org/), ob ein solches Verhalten jemals vollständig gepatcht werden kann.

### Laufzeitverbesserungen {#laufzeitverbesserungen}

Laufzeitverbesserungen ändern das Modell nicht, sondern verbessern die Art und Weise, wie das Modell verwendet wird.

Die einfachste dieser Verbesserungen ist die Änderung der Prompts.
Selbst kleine Änderungen an den Prompts können einen großen Effekt auf die Ausgabe des Modells haben.
Das Hinzufügen einiger Wörter zu einem Prompt kann die Leistung [um über 50% verbessern](https://arxiv.org/pdf/2309.03409.pdf).

Aber wir können auch alle möglichen Software verwenden, um ein Basis-Modell zu erweitern.
Zum Beispiel haben Menschen Möglichkeiten gefunden, ein Langzeitgedächtnis zu GPT-4 hinzuzufügen, indem sie das Modell eine Datenbank abfragen lassen.
Oder betrachten Sie AutoGPT, das ein Modell rekursiv aufrufen lässt, was bedeutet, dass es autonom für beliebige Zeiträume laufen kann.
Oder betrachten Sie [Voyager](https://arxiv.org/abs/2305.16291), ein Tool, das GPT-4 ermöglichte, Minecraft vollständig autonom zu spielen. Es bekam sogar Diamant-Ausrüstung.

Wir wissen nicht, wie weit ein Basis-Modell gestreckt werden kann.
Selbst wenn wir jetzt aufhören, neue KI-Modelle zu trainieren, werden wir wahrscheinlich wichtige Innovationen sehen, die neue Fähigkeiten zu bestehenden Modellen hinzufügen.

## Fazit {#fazit}

Gefährliche Fähigkeiten von KI können zu allen möglichen Problemen führen: groß angelegten Cyberangriffen, entwickelten Pandemien und Rogue-KI, die [die Kontrolle übernimmt](/ai-takeover).
Es ist verlockend, sich auf Bewertungen zu verlassen, um diese gefährlichen Fähigkeiten zu verhindern oder zu verbreiten, aber dies ist ein gefährlicher Ansatz:

- Selbst wenn wir Modelle vor dem Einsatz testen, gibt es immer noch Möglichkeiten, wie sie gefährliche Fähigkeiten nach dem Einsatz erhalten können (Feinabstimmung, Jailbreaking, Laufzeitverbesserungen).
- Modelle können geleakt werden.
- Einige Fähigkeiten sind sogar gefährlich innerhalb von KI-Labors.

Die einzige sichere Option ist, diese leistungsfähigen KI-Systeme nicht zu bauen.
Wir sollten die Erstellung dieser unvorhersehbaren, potenziell hochgefährlichen KI-Systeme nicht zulassen.
[Leider verhindert kein einziger Entwurfsvorschlag derzeit die Entwicklung oder verzögert die Entwicklung von superintelligenter KI.](https://twitter.com/PauseAI/status/1704998018322141496)
Deshalb fordern wir eine [Pause](/proposal)!