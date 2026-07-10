
# Herzkompass

Dieses Repository enthält die veröffentlichten Herzkompass-Analysen und die zugehörige Übersichtsseite.

## GitHub Pages

Die veröffentlichte Startseite ist hier erreichbar:

https://lilu3013.github.io/herzkompass/

## Repository-Struktur

```text
herzkompass/
├── index.html
├── analysen/
├── archiv/
└── README.md
```

### `index.html`

Die zentrale Startseite des Projekts.

Sie liest automatisch alle passenden HTML-Dateien aus dem Ordner `analysen/` aus und zeigt sie als Liste an.

### `analysen/`

Hier liegen die aktuell veröffentlichten Herzkompass-Analysen.

Damit eine Datei automatisch auf der Startseite erscheint, muss sie nach diesem Schema benannt sein:

```text
herzkompass_name.html
```

Beispiele:

```text
herzkompass_britta.html
herzkompass_clarissa.html
herzkompass_daniel.html
```

### `archiv/`

Hier können ältere oder nicht mehr aktive Dateien aufbewahrt werden.

Dateien in diesem Ordner werden nicht auf der Startseite angezeigt.

## Arbeitsweise

- Neue Analysen werden als vollständige HTML-Dateien erstellt.
- Die Dateien werden in den Ordner `analysen/` hochgeladen.
- Die Startseite aktualisiert sich danach automatisch.
- Bestehende Dateien werden vor Änderungen zuerst geprüft.
- Änderungen werden einzeln durchgeführt und anschließend getestet.

## Ziel

Das Repository soll:

- übersichtlich bleiben
- langfristig wartbar sein
- GitHub Pages optimal nutzen
- HTML-Dateien einfach veröffentlichen
- Links einfach teilbar machen
- auf Smartphone, Tablet und PC sauber funktionieren
