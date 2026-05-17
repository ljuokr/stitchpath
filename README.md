# StitchPath

Browser-basierter Stickdaten-Editor — eine Single-File-HTML-App zum Zeichnen, Skalieren und Exportieren von Stickmustern im **DST**-Format.

Inspiriert vom Hardware-Plotter-Stickfont-Ansatz (Hershey) und am Workflow von Sticker-Anfängern (Schule, Bastelei, Hobby) ausgerichtet.

## Features

- **Drei Stichtypen**: Geradstich, Mehrfach (echte parallele Bahnen), Zickzack/Satin
- **Text-Werkzeug** mit eingebauter Hershey-Strichschrift, frei drehbar, in Geradstich / Mehrfach / Satin
- **Vorlage importieren** (Bild) und verschieben / drehen / skalieren / spiegeln
- **Stickrahmen-Vorwahl** für gängige Modelle (130×100, 200×200, Mega Hoop, Magic Hoop, etc.)
- **Multi-Touch**: Pinch-Zoom und Two-Finger-Pan auf iPad / Smartphone
- **Auto-Glättung** bei breiten Satin-Bahnen (mm-basierte Tiefpass-Filterung), schaltet sich beim Radieren automatisch ein, damit der Rest der Bahn nicht reformiert wird
- **Echte Maschinenausgabe**: DST mit Tie-In/Tie-Off, automatischer Long-Stitch-Subdivision, JUMP-Stichen zwischen Bahnen
- **Stickzeit-Schätzung** basierend auf realistischer Maschinengeschwindigkeit (~850 Stiche/min)
- **Projekt-Speichern/Laden** als JSON, DST-Import inklusive
- **Auto-Save** im LocalStorage
- Sticht im Browser – läuft offline, eine HTML-Datei.

## Benutzung

Öffne `StitchPath.html` in einem aktuellen Browser (Chrome, Safari, Firefox).
- Mit der Maus / dem Finger auf den Stickrahmen zeichnen
- Stichtyp links auswählen, Breite und Stichlänge anpassen
- Radierer / Linie-Verschieben über die "Korrigieren"-Sektion
- Über "Speichern" als `.dst`-Datei exportieren

## Lizenz

CC BY-NC 4.0 — © 2026 Lukas Jordi

Frei nutzbar für private, schulische und nicht-kommerzielle Zwecke. Kommerzielle Nutzung nur mit schriftlicher Genehmigung des Autors.

## Status

Experimentell. Keine Gewähr dafür, dass die exportierten Stickdateien fehlerfrei auf einer Stickmaschine laufen. Vor dem Sticken sollte die Datei mit einem Stickmaschinen-Viewer oder direkt auf einem Probestück getestet werden.
