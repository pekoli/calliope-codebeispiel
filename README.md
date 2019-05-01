# calliope-codebeispiel
yotta-Projektvorlage für C/C++ auf Calliope mini

Beispielprojekt zum Posting [Calliope mini offline in C programmieren - Teil 1](https://www.moabot.de/2019/05/02/calliope-mini-offline-in-c-programmieren-teil-1).

Dieses yotta-Projekt enthält folgende Dateien:
- `module.json`: Setzt den Projektnamen und bindet die [Calliope-C-Bibiotheken](https://github.com/calliope-mini/microbit) ein.
- `config.json`: deaktiviert Bluetooth um Speicherplatz zu sparen.
- `.yotta.json`: setzt die Calliope als Zielarchitektur.
- source/HalloWelt.cpp: C-Beispielprogramm, das "Hallo Welt!" auf der LED-Matrix der Calliope ausgibt.

Bauen Sie das Projekt mit:
```
git clone https://github.com/pekoli/calliope-codebeispiel.git
cd calliope-codebeispiel/
yotta build
```

Ein eigenes Projekt auf Basis dieses Beispielprojekts erstellen:
1. Kopieren Sie das Projektverzeichnis in ein neues Verzeichnis: `cp -r calliope-codebeispiel/ mein-projekt`.
2. Wechseln Sie in das neue Projektverzeichnis: `cd mein-projekt/`.
3. Editieren Sie die Datei `module.json`: Ändern Sie den Projektnamen von `calliope-codebeispiel` zu `mein-projekt`.

