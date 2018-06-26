# Was ist PoetryBot?

PoetryBot erschafft expressive, absurde, interessante und oft richtig blöde Internet-Poesie aus visuellem Input.

PoBo [PoetryBot] spricht Deutsch und Englisch und verwendet Fotos aller Art, zB von deinem Handy. PoBo ist einfach zu nutzen und verbindet Fotografieren mit Dichten. So wird Poesie für wirklich jede_n ganz leicht herstellbar, zum Beispiel für Schüler_innen im Deutschunterricht, Pensionisten mit Smartphone (oder natürlich für edgy Trendsetter wie dich).

# Wie kann ich PoetryBot verwenden?

Derzeit ist PoBo noch nicht fertig.

PoBo kann zwar schon sehr viel, ist aber noch sehr schwierig zu verwenden. Außerdem fehlt natürlich noch eine stylische Website, die das Online-Dichten für dich zu einer super Erfahrung macht. Eine Erfahrung, die so toll ist, dass du gar nicht mehr aufhören möchtest - versprochen!

# OK, aber welche Features sind denn geplant?

PoBo wird in zwei Versionen entwickelt. Zuerst kommt die einfache und schlanke erste Version (Alpha), dann die fortgeschrittene und mit Profi-Features vollgepackte zweite Version (Beta).

### Das kannst du in der Alpha machen:

1) Foto hochladen

2) Automatisch generiertes Gedicht lesen

3) Überschrift hinzufügen und Gedicht verbessern [wenn du möchtest]

4) Gedicht als PDF herunterladen und versenden / drucken

### Für die Beta haben wir uns ein paar ziemlich coole Sachen überlegt:

* **Schreibstil anpassen**

Wäre es nicht cool, wenn du die Persönlichkeit von PoBo anpassen könntest? Die Worte, die PoBo zum Dichten verwendet, hängen von den Texten ab die du ihm fütterst. Du kannst PoBo also die Persönlichkeit von berühmten Literaten wie Kafka oder Camus geben, um richtig schöne Gedichte zu bekommen. Oder du gibst PoBo nur Internettexte und schaust, was da lustiges rauskommt - deine Entscheidung!

* **Schlüsselwörter eintippen**

Wenn du ein Bild hochlädst, erkennt PoBo was darauf zu sehen ist. Vielleicht möchtest du aber über Himbeeren schreiben, hast aber gerade keine herumliegen. Oder Löwen! Deshalb kannst du statt einem Bild auch ein oder mehrere Wörter eintippen, die dann für die automatische Generierung deines Poems verwendet werden.

* **Bild bearbeiten**

Du hast ein tolles Foto von deinen neuen Sneakers gemacht und daraus ein Gedicht generiert. Das Gedicht ist richtig cool, aber das Foto könnte noch ein bisschen flashiger sein - kein Problem! Färb dein Foto so bunt wie du willst und schneide einen Teil vom Rand weg.

* **Poems veröffentlichen**

Nach ein bisschen Herumprobieren machst du ein Poem, das richtig cool geworden ist. Du möchtest es anderen zeigen und damit angeben. Kein Problem! Speichere es einfach auf der Website mit oder ohne deinem Namen und vergleiche es mit den Poems von anderen Leuten.

# Bitte, bitte, schickt mir Updates!

PoBo hat einen Newsletter, der dich monatlich mit brandneuen Infos versorgt. Bis die erste Version (Alpha) fertig ist, gibt es noch viele spannende Zwischenschritte in der Entwicklung, die du nicht verpassen möchtest.

### So bleibst du up-to-date

Schick uns einfach eine kurze Mail an **thepoetrybot@gmail.com** mit deinem Vor- & Nachnamen und was du so machst (Schule, Studium, Beruf). Wir freuen uns auch über jede Art von Feedback - damit hilfst du uns, PoBo so gut wie möglich zu machen!

# Und wer sind eigentlich die nicen Leute hinter PoetryBot?

Wir sind drei kreative Typen mit einer Vision. Viele sagen, dass Gedichte schreiben richtig schwierig ist. Das ist aber Blödsinn. Jede_r kann Schreiben!  Wir wollen Poesie demokratisieren, das heißt: für alle ganz einfach machen, egal ob Anfänger oder Profi.

![Foto Team]()

Wir sind Fabian, Alexander und Florian (ja genau, die auf dem Foto!)

Fabian schreibt richtig gerne und ist ein Druck-Fan. Alexander ist ein super Programmierer und generell ein Problemlöser. Florian ist mit Abstand der Sozialste von uns und liebt es, mit verschiedensten Menschen zusammenzuarbeiten.

# Aber jetzt mal ernsthaft: wie funktioniert das eigentlich? [Achtung technisch]

PoBo ist derzeit in Processing (Java) programmiert. Hinter diesem öffentlich [auf GitHub einsehbaren Repository](https://github.com/axr95/PoetryBot/) stehen zwei verschiedene Methoden zur automatischen Gedichterstellung.

* **Markov Chain**

Das einfachere, technisch voll ausgereifte Verfahren nutzt das Prinzip der Markov-Kette (oder auch: Markov Chain). Derzeit verwenden wir diese Technik zur Gedichterstellung, was super klappt und sehr kreative Texte entstehen lässt.

Hier werden für alle Wörter des verwendeten Quelltexts (zB drei Bücher von verschiedenen Autoren) die Wahrscheinlichkeiten für nachfolgende Wörter ermittelt. Basierend auf diesen je nach Text verschiedenen Wahrscheinlichkeiten wird dann für jedes einzelne Wort ein Nachfolgewort auf zufälliger Basis ermittelt. [Mehr dazu erfährst du hier.](https://fabiandietrich.com/poetrybot/)

* **Machine Learning**

Das zweite Verfahren ist deutlich kniffliger und noch in Entwicklung.

Mittels Machine Learning wollen wir hier verschiedene literarische Vektormodelle erstellen, die ihren Output kontextabhängig anpassen. Zum Beispiel soll damit bei Eingabe der Wörter "Sonne" und "Kirsche" der Output-Text signifikant sonniger (positiver/optimistischer) und kirschiger (fruchtiger) werden. Wir experimentieren hier derzeit im Bereich Natural Language Processing mit der word2vec-Technik und dem vortrainierten GloVe-Modell.

# Ich hab eine Frage / möchte mitmachen!

Cool, das freut uns sehr! :) Schreib uns einfach jede Frage, die dich interessiert an **thepoetrybot@gmail.com**

Wenn du überlegst mitzumachen und du ein bisschen (oder sehr gut) Programmieren kannst, schau doch mal in [unserem GitHub-Repository](https://github.com/axr95/PoetryBot/) vorbei. PoBo ist derzeit in einer Mischung aus Processing (Java) und Python geschrieben.

Auch wenn du nicht Programmieren kannst, bist du herzlich im Team willkommen. Du kannst uns zum Beispiel beim Designen, Promoten oder Workshop-Organisieren helfen!


**PoetryBot (c) 2018**
