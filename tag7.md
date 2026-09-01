# Tag 7 – Branch mergen und löschen

## Was habe ich gelernt?

Heute habe ich gelernt, wie ich einen Feature-Branch direkt über das Terminal in `main` übernehme und anschließend lösche.

## Feature-Branch in main übernehmen

Zuerst auf `main` wechseln:

`git switch main`

Den aktuellen Stand von GitHub holen:

`git pull`

Den Feature-Branch in `main` mergen:

`git merge feature`

Den neuen Stand zu GitHub hochladen:

`git push`

## Branch danach löschen

Lokalen Branch löschen:

`git branch -d feature`

Branch auch auf GitHub löschen:

`git push origin --delete feature`

## Kompletter Ablauf

`git switch main`

→ `git pull`

→ `git merge feature`

→ `git push`

→ `git branch -d feature`

→ `git push origin --delete feature`

## Erkenntnis des Tages

Nach einem erfolgreichen Merge enthält `main` die Änderungen aus meinem Feature-Branch.

Wenn ich den Feature-Branch danach nicht mehr brauche, kann ich ihn lokal und auf GitHub löschen.


