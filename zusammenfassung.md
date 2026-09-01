# Zusammenfassung

In den letzten 7 Tagen habe ich die Grundlagen von Git, GitHub und dem Terminal gelernt.

## Terminal Grundlagen

- `pwd` – zeigt mir, in welchem Ordner ich bin
- `ls` – zeigt mir Dateien und Ordner
- `cd Ordnername` – wechselt in einen Ordner
- `cd ..` – geht eine Ebene zurück
- `mkdir Ordnername` – erstellt einen neuen Ordner
- `touch datei.md` – erstellt eine neue Datei
- `nano datei.md` – öffnet und bearbeitet eine Datei
- `mv altername neuername` – benennt Dateien oder Ordner um
- `rm datei.md` – löscht eine Datei

## Git Grundlagen

- `git init` – erstellt ein Git-Repository
- `git status` – zeigt den aktuellen Git-Status
- `git add datei.md` – bereitet eine Datei für den Commit vor
- `git add .` – bereitet alle Änderungen vor
- `git commit -m "Nachricht"` – speichert einen neuen Versionsstand
- `git log --oneline` – zeigt meine bisherigen Commits

## GitHub

- `git remote -v` – zeigt die Verbindung zu GitHub
- `git push` – lädt meine Commits zu GitHub hoch
- `git pull` – holt den aktuellen Stand von GitHub

## Branches

- `git branch` – zeigt alle Branches
- `git switch main` – wechselt zu `main`
- `git switch feature` – wechselt zu einem Feature-Branch
- `git switch -c feature2` – erstellt einen neuen Branch und wechselt direkt dorthin
- `git push -u origin feature2` – lädt einen neuen Branch zum ersten Mal zu GitHub hoch

## Pull Request und Merge

Ein Pull Request überträgt Änderungen von einem Feature-Branch in `main`.

Auf GitHub:

`feature` → `main`

Danach kann der Pull Request gemerged werden.

Direkt im Terminal geht ein Merge mit:

`git switch main`

`git pull`

`git merge feature`

`git push`

## Branch löschen

- `git branch -d feature` – löscht einen lokalen Branch
- `git push origin --delete feature` – löscht den Branch auch auf GitHub

## Wichtigster Workflow

`Datei ändern`

→ `git add`

→ `git commit`

→ `git push`

→ Pull Request

→ Merge

→ `git pull`

Mein wichtigstes Learning:

Git hilft mir dabei, Änderungen sauber zu speichern, verschiedene Entwicklungsstände über Branches zu trennen und diese anschließend kontrolliert wieder in `main` zusammenzuführen. 

