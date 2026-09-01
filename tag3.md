# Tag 3 – Arbeiten mit Branches

## Was habe ich gelernt?

Heute habe ich gelernt, wie man in Git einen neuen Branch erstellt und warum Branches verwendet werden.

Ein Branch ist wie ein Seitenstrang meines Projekts. Ich kann dort Änderungen machen, ohne direkt meinen Haupt-Branch `main` zu verändern.

## Neue Befehle

- `git status` – zeigt mir den aktuellen Zustand meines Git-Repositories
- `git switch -c feature/tag3` – erstellt einen neuen Branch und wechselt direkt auf diesen Branch
- `git branch` – zeigt mir alle vorhandenen Branches
- `git push -u origin feature/tag3` – lädt den neuen Branch zum ersten Mal zu GitHub hoch

## Was bedeutet der Stern bei `git branch`?

Wenn ich `git branch` eingebe, sehe ich zum Beispiel:

`* feature/tag3`
`main`

Der Stern `*` zeigt mir, auf welchem Branch ich mich gerade befinde.

## Was habe ich über Branches verstanden?

Mein Haupt-Branch heißt `main`.

Wenn ich einen neuen Branch erstelle, basiert dieser zunächst auf dem aktuellen Stand von `main`.

Danach kann ich auf dem neuen Branch unabhängig weiterarbeiten.

Zum Beispiel:

`main`
↓
`feature/tag3`

Änderungen auf `feature/tag3` verändern `main` zunächst nicht.

## Mein Workflow mit einem Branch

`main`

→ neuen Branch erstellen

→ `feature/tag3`

→ Datei bearbeiten

→ `git add`

→ `git commit`

→ `git push`

→ Pull Request erstellen

→ Branch wieder mit `main` zusammenführen

## Erkenntnis des Tages

Branches ermöglichen es, neue Änderungen getrennt vom Hauptprojekt zu entwickeln.

Dadurch kann ich Änderungen erst fertigstellen und überprüfen, bevor sie später über einen Pull Request in `main` übernommen werden. 
