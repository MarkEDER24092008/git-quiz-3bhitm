# GIT Quiz - Angabe

## Aufgabenstellung
**Name:** Mark Leon Eder  

### Ziel
Zeige in diesem Quiz, dass du die Grundlagen von Git verstanden hast.
Du arbeitest strukturiert mit Branches, führst saubere Commits durch und kannst eine bestehende Git-History analysieren.

### Aufgaben

1. **Repository duplizieren = FORK (2 Punkte)**
   - Erstelle ein Duplikat = FORK des Repositories in deinem eigenen Account. 
   - Klone das Repository auf deinen lokalen Rechner.

2. **Erste Commits durchführen (3 Punkte)** 
   - Öffne die Datei index.html. 
   - Ergänze in der Datei eigenen Code an der markierten Stelle. 
   - Stage die Änderung. Erstelle einen sinnvollen Commit mit einer aussagekräftigen Message. Die Commit-Message wird bewertet!

3. **Branches erstellen (4 Punkte)**
   - Erstellen Sie einen Branch `commit-branch`. 
   - Wechsle auf diesen Branch. 
   - In diesem Branch sollst du das File `index.html` überarbeiten. 
   - Du findest dort einen Bereich mit schlechten Commit-Messages. KOPIERE den Bereich, und verbessere die Nachrichten.
commit 5bf9e95f7e3d02ba5d1acb01cd8a607a933add95 (HEAD -> commit-branch, origin/commit-branch)
Author: Mark <m.eder4@students.htl-leonding.ac.at>
Date:   Wed Feb 25 08:13:13 2026 +0100

    Name insertion in index file

commit d87473dd086df3d59580b07c73f8f26b828ec509
Author: Natascha Rammelmüller <n.rammelmueller@htl-leonding.ac.at>
Date:   Wed Feb 25 07:10:45 2026 +0100

    feature

commit f7f599d0b0e0f5f5d6a12bc7cf697f3a664b6b04
Author: Natascha Rammelmüller <n.rammelmueller@htl-leonding.ac.at>
Date:   Wed Feb 25 07:09:32 2026 +0100

    new

commit 8be24db117802b8ebe2f24ea2d230426244d5a73
Author: Natascha Rammelmüller <n.rammelmueller@htl-leonding.ac.at>
Date:   Wed Feb 25 07:09:10 2026 +0100

    add

commit db8992f5f4a93be4face083f50619a81cefcf928
Author: Natascha Rammelmüller <n.rammelmueller@htl-leonding.ac.at>
Date:   Wed Feb 25 07:08:41 2026 +0100

    cleanup code

commit dd866aeeaf54cf369f54d29b121006314b6a1caa
Author: Natascha Rammelmüller <n.rammelmueller@htl-leonding.ac.at>
Date:   Wed Feb 25 07:07:55 2026 +0100

    update index

commit a2f58c5cd469510e720b4884737fe773cf778419
Author: Natascha Rammelmüller <104194982+nrammelmueller@users.noreply.github.com>
Date:   Wed Feb 25 07:06:53 2026 +0100

    init files for quiz

commit 6215e026e4bf13c6c962a9be29ffe2ab48f7581c
Author: Natascha Rammelmüller <104194982+nrammelmueller@users.noreply.github.com>
Date:   Mon Feb 23 11:34:41 2026 +0100


   - Stagen und Commiten. Achtung: AM BRANCH!

5. **Merge-Conflict provozieren (5 Punkte)**
   - Wechsle nun zurück zum Hauptbranch `main` und bearbeite auch hier die Datei `index.html`. Ergänze an der gleichen Stelle wie im Branch `commit-branch` eigenen Code.
   - Stagen und Commiten. Achtung: AM HAUPTBRANCH!
   - Nun versuche den Branch `commit-branch` in den Hauptbranch `main` zu mergen.
   - Es sollte ein Merge-Conflict entstehen. Löse diesen korrekt.
   - Committe die Lösung.
Antwort: Lösungsweg: im terminal auf mit 'git switch main' switchen, und mit 'git merge commit-branch' mergen. Bei Konflikt 'git add .' verwenden, dann wieder commiten.
     
  

6. **GIT-History analysieren (4 Punkte)**
Schaue dir nun die komplette Commit-History an. Denn im aktuellen Projekt funktioniert die Navigation nicht korrekt. Finde heraus, in welchem Commit der Fehler eingeführt werde. Beschreibe kurz / gibt die Commit-ID an. Mit welchem Befehl hast du dies herausgefunden? Wie viele Commits wurden insgesamt in diesem Projekt erstellt?
Antwort: Im commit "Add" wurden die Navigationselemente entfernt.
Commit Id: 8be24db117802b8ebe2f24ea2d230426244d5a73
Insgesamt wurden 7 Commits vor meinem Forking erstellt 
----------------------- 

Du hast das Quiz nun erfolgreich abgeschlossen. Gib HIER den Link zu deinem geforkten Repository an: 
https://github.com/MarkEDER24092008/git-quiz-3bhitm.git

Gib anschließend dieses ANGABE-File bei MOODLE ab!

