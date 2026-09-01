# Tag 6 – Pull Request und Merge

## Was habe ich gelernt?

Heute habe ich gelernt, wie ich Änderungen von einem Feature-Branch wieder in `main` übernehme.

Dafür habe ich auf GitHub einen Pull Request erstellt.

## Pull Request

Ein Pull Request bedeutet:

`feature` → `main`

Damit schlage ich vor, meine Änderungen aus dem Feature-Branch in den Haupt-Branch zu übernehmen.

## Was habe ich gemacht?

- auf dem Feature-Branch gearbeitet
- `git add`
- `git commit`
- `git push`
- auf GitHub `Compare & pull request` gewählt
- geprüft: `base: main` und `compare: feature`
- Pull Request erstellt
- anschließend den Pull Request gemerged

## Was bedeutet Merge?

Beim Merge werden die Änderungen aus meinem Feature-Branch in `main` übernommen.

Danach enthält `main` auch die neuen Änderungen.

## Nach dem Merge

Zurück auf `main` wechseln:

`git switch main`

Aktuellen Stand von GitHub holen:

`git pull`

## Kurz gesagt

Feature-Branch erstellen  
→ Änderungen machen  
→ committen  
→ pushen  
→ Pull Request  
→ Merge  
→ zurück zu `main`  
→ `git pull`

## Erkenntnis des Tages

Ein Pull Request hilft dabei, Änderungen kontrolliert von einem Branch in `main` zu übernehmen.


