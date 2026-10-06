## Der OCEAN-Abfrageprozess

<html>
<br>
  <div style="position: relative; overflow: hidden; padding-top: 56.25%;">
    <iframe style="position: absolute; top: 0; left: 0; right: 0; width: 100%; height: 100%; border: none;" src="https://www.youtube.com/embed/bRkeVdvYcTU?rel=0&cc_load_policy=1" allowfullscreen allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share">
    </iframe>
  </div>
</html>

Eine "Eingabeaufforderung" für große Sprachmodelle (GSM) ist der Text, den du dem Modell gibst, um eine Antwort zu erhalten. Es ist wie eine Frage zu stellen oder einen Ausgangspunkt für das Modell zu erstellen Text. Wenn du zum Beispiel Erzähl mir einen Witz eingibst, — das ist deine Eingabeaufforderung — dann sollte das Modell mit einem Witz antworten.

Wenn du zum Beispiel Erzähl mir einen Witz eingibst, — das ist deine Eingabeaufforderung — dann sollte das Modell mit einem Witz antworten.

### Ziele

Entscheide, was du erreichen möchtest. Das ist dein Ziel, wenn du das Sprachmodell nutzt. Formuliere dies in deiner Eingabeaufforderung und gib klar an, **was du am Ende vom GSM haben möchtest**.

\--- task ---

Beginne deine Eingabeaufforderung mit einem **Ziel**, das mit „Ich möchte Hilfe beim Erstellen von **etwas**“ beginnen sollte.

Zum Beispiel:

"Ich möchte Hilfe beim Erstellen eines **Rezepts für ein einfaches Dessert**."
"Ich möchte Hilfe beim Erstellen einer **Kurzgeschichte**."
"Ich möchte Hilfe beim Erstellen eines **Lernplans für meine Geschichtsprüfungen**."

\--- /task ---

### Kontext

Gib Hintergrundinformationen an, damit das Modell deine Anfrage besser verarbeiten kann. Füge wichtige Informationen hinzu, wie Länge, Zielgruppe, Tonfall und bestimmte Fakten, die du einbeziehen möchtest.

\--- task ---

Gib deiner Eingabeaufforderung **Kontext**.

Zum Beispiel:

Ich möchte Hilfe beim Erstellen eines Rezepts für ein einfaches Dessert. **Mache das Rezept kinderleicht verständlich, mit Zutaten, die zu Hause gefunden werden können.**

\--- /task ---

### Beispiele

Zeige, welche Art von Antworten du suchst, indem du **Beispiele** angibst. Das hilft dem Modell, die Anfrage richtig zu verstehen. Du kannst Beispiele für andere Rezepte geben, die dir gefallen, Dinge, die unbedingt enthalten sein sollen, oder Schreibweisen von Rezepten, die dir gefallen haben.

\--- task ---

Füge deiner Eingabeaufforderung **Beispiele** hinzu.

Zum Beispiel:

Ich möchte Hilfe beim Erstellen eines **Rezepts für ein einfaches Dessert**. Mache das Rezept kinderleicht verständlich, mit Zutaten, die zu Hause gefunden werden können. **Ich mag Rezepte, die kreative Elemente enthalten, wie das Dekorieren mit Streuseln oder das Hinzufügen von Zuckerguss**. Schreibe das Rezept mit einer klaren Liste von Zutaten, mit der Methode in nummerierten Schritten.\*\*"

\--- /task ---

### Bewerten

Auch wenn es vielleicht so scheint, verstehen GSM nichts so wie Menschen. Stattdessen wählen GSM einfach das **nächstbeste Wort**, indem sie Muster in der Sprache vorhersagen. Sie sind im Grunde nur wie eine ausgefeilte Autovervollständigung. Manchmal geben sie falsche oder ungerechte Informationen aus, und **du** musst vorsichtig sein, damit du keine Probleme bekommst, weil du die Ausgabe nicht richtig überprüft hast.

\--- task ---

Überprüfe, ob die Antwort dem entspricht, was du wolltest. Achte auf Fehler oder Dinge, die keinen Sinn ergeben.

Zum Beispiel:

- Listet das Rezept alle Zutaten und Schritte klar auf?
- Gibt es einen Schritt für eine lustige Dekoration?
- Gibt es ungewöhnliche Zutaten oder Methoden, die gefährlich sein könnten?
- Gibt es Teile des Textes, die in Bezug auf Fakten falsch sind?
- Gibt es Dinge, die du nicht verstehst?

\--- /task ---

### Verhandeln

Wenn die Antwort nicht ganz passt, bitte das GSM, Änderungen vorzunehmen. Sei genau darin, was korrigiert werden muss. Behandle das LLM wie einen Projektpartner, der nicht sehr gut ist - überprüfe die Arbeit zweimal, um sicherzugehen, dass alles in Ordnung ist, und sorge dann dafür, dass das LLM alle Fehler oder Dinge, die dir nicht gefallen, korrigiert.

\--- task ---

Schlage dem GSM Änderungen und Korrekturen vor.

Zum Beispiel:

Fast richtig, aber noch nicht ganz. Du hast die Methodenschritte nicht gezählt, und ich habe keine dunkle Schokolade im Schrank. Auch die Verwendung eines Schweißbrenners ist mir nicht gestattet

\--- /task ---

**Wichtigster Schritt: Die menschliche Bearbeitung**

\--- task ---

Überprüfen Sie die Antwort ein letztes Mal, um sicherzustellen, dass sie leicht zu verstehen, zu korrigieren und vollständig ist. Es wird der Moment kommen, an dem es einfacher ist, die Wörter und Kleinigkeiten, die dir nicht gefallen, selbst zu ändern, statt das GSM immer wieder darum zu bitten.

**Es liegt ganz bei dir (der Person), sicherzustellen, dass das Werkzeug, das du verwendest, richtig funktioniert und dass seine Ausgabe nicht dazu verwendet wird, Schaden anzurichten.**

\--- /task ---

Im nächsten Schritt wirst du dir ansehen, wie man eine **Rolle** für ein LLM festlegt.
