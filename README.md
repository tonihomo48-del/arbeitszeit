# Arbeitszeiten App - APK bauen

1. Dieses ZIP entpacken.
2. Auf github.com anmelden (kostenloses Konto) und oben rechts "New repository" waehlen. Name: arbeitszeiten, "Create repository".
3. Auf der neuen Seite den Link "uploading an existing file" anklicken.
4. Den INHALT des entpackten Ordners (www, .github, package.json, capacitor.config.json, .gitignore) per Drag and Drop ins Browserfenster ziehen. Dann unten "Commit changes".
5. Oben auf "Actions" klicken. Der Build startet von selbst und dauert etwa 5 Minuten. Wenn nicht: links "APK bauen" waehlen, dann "Run workflow".
6. Wenn der Lauf einen gruenen Haken hat: Lauf anklicken, ganz unten bei "Artifacts" die Datei "arbeitszeiten-apk" herunterladen und entpacken. Darin liegt app-debug.apk.
7. app-debug.apk aufs Handy kopieren (USB-Kabel, Cloud oder E-Mail), antippen und installieren. Beim ersten Mal muss das Installieren aus dieser Quelle erlaubt werden. Falls Play Protect warnt: "Trotzdem installieren".

Falls der Ordner .github beim Hochladen fehlt: im Repository "Add file" > "Create new file", als Name
.github/workflows/build-apk.yml
eintippen und den Inhalt der gleichnamigen Datei aus diesem ZIP einfuegen.
