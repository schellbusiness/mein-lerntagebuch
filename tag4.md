# Tag 4 – Branches pushen und wechseln

## Was habe ich gelernt?

Heute habe ich gelernt, dass ein neuer Branch zuerst nur lokal auf meinem Mac existiert.

Mein Branch heißt:

`feature`

Ich habe meine Datei `tag3.md` auf diesem Branch erstellt und committed.

## Wichtige Befehle

- `git branch` – zeigt mir alle lokalen Branches
- `git switch feature` – wechselt auf den Branch `feature`
- `git switch main` – wechselt zurück auf den Haupt-Branch `main`
- `git push -u origin feature` – lädt den Branch `feature` zum ersten Mal zu GitHub hoch
- `git push` – reicht bei späteren Änderungen, wenn der Branch bereits mit GitHub verbunden ist

## Was bedeutet `git push -u origin feature`?

`git push`
→ lädt meine lokalen Commits zu GitHub hoch

`-u`
→ Git merkt sich die Verbindung zwischen meinem lokalen Branch und dem Branch auf GitHub

`origin`
→ Name meines GitHub-Repositories

`feature`
→ Name des Branches, den ich hochladen möchte

Nach dem ersten Push ist mein Branch also lokal und auf GitHub vorhanden.

## Wie wechsle ich zwischen meinen Branches?

Wenn ich sehen möchte, welche Branches es gibt:

`git branch`

Zum Beispiel:

`* feature`
`main`

Der Stern zeigt, auf welchem Branch ich mich gerade befinde.

Zurück zu `main` wechseln:

`git switch main`

Wieder auf `feature` wechseln:

`git switch feature`

## Wichtig

Bevor ich einen Branch wechsle, sollte ich mit

`git status`

prüfen, ob ich noch ungespeicherte Änderungen habe.

Wenn dort steht:

`nothing to commit, working tree clean`

kann ich den Branch problemlos wechseln.

## Mein Workflow

`git branch`

→ prüfen, auf welchem Branch ich bin

→ Datei bearbeiten

→ `git add`

→ `git commit`

→ beim ersten Mal `git push -u origin feature`

→ später nur noch `git push`

→ mit `git switch main` zurück zu main

## Erkenntnis des Tages

Ein Branch kann unabhängig vom Haupt-Branch weiterentwickelt werden.

Ich kann zwischen `main` und `feature` wechseln und dadurch verschiedene Entwicklungsstände meines Projekts getrennt voneinander bearbeiten.
