# DHBW.LaTeX_Template
Eine Vorlage für Studien-/Projekt-/Bachlorarbeit an der DHBW.

Die Vorlage ist so aufgebaut, dass im Verzeichnis `template` kaum Änderungen vorgenommen werden müssen.
Die Bilder in `template/figures` können ausgetauscht und deren Größe sowie Position angepasst werden.
Alle anderen Werte sind in der Datei `main.tex` in den ersten beiden Abschnitten konfigurierbar.

Neue Kapitel können in dem Verzeichnis `chapters` abgelegt werden. In `main.tex` muss diese Datei als Input ergänzt werden:  
```
%% Add new chapters here
...
\input{chapters/myChapterName}
```

## Hinweis bei der Verwendung von Overleaf.com
Nach dem Hochladen der Dateien muss in den Einstellungen `main.tex` als **Main document** festgelegt werden.