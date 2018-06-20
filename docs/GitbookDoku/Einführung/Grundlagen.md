# Grundlagen
Industrie 4.0, IoT, CI/CD, dockerized... Kein anderes Fachgebiet scheint über die Jahre hinweg so vielen Buzzwords ausgesetzt wie die Informatik. Allein in einem Teammeeting innerhalb des IT Bereichs kann ein normalsterblicher, so scheint es, schon keiner Konversation folgen, ohne einen Thesaurus bei der Hand zu haben, der ihm in die Magie der Thematik einzuführen vermag.

Ziel dieses Buches ist es anhand einer Studienarbeit einen möglichst großen Querschnitt über alle Themengebiete zu geben.

## Verzeichnis Struktur {#struktur}

Die untere Abbildung zeigt die Verzeichnisstruktur der Beispielanwendung.

Hierbei ist das Verzeichnis **cookbooks** die Wurzel, die alle Kochbücher verwaltet.
Das Kochbuch **beleg** besteht aus den einzelnen Rezepten (**recipes**).
Das Verzeichnis **files/default** beinhaltet Dateien wie Textdateien oder diverse Skripte, welche in vereinzelten Rezepten benötigt werden.

```
.
├── cookbooks
│   ├── beleg
│       ├── attributes
│       ├── files
│       │   └── default
│       ├── recipes
│       ├── spec
│       │   └── unit
│       │       └── recipes
│       ├── templates
│       └── test
│           └── smoke
│               └── default
│   
│   

```
