# Digitaler Kompetenzcheck für Lehrkräfte

Diese kleine Webanwendung ist für GitHub Pages vorbereitet.

## Zweck

Der Check ist **kein schulweiter Fragebogen mit zentraler Datensammlung**, sondern ein persönliches Reflexionsinstrument für Lehrkräfte.

Er enthält folgende Bereiche:

1. Professionelles digitales Handeln
2. Digitale Ressourcen
3. Lehren und Lernen
4. Diagnose, Feedback und Lernbegleitung
5. Lernendenorientierung und Differenzierung
6. Förderung der KMK-Kompetenzen der Schülerinnen und Schüler
7. Künstliche Intelligenz im Unterricht
8. Rahmenbedingungen
9. Persönlicher nächster Entwicklungsschritt

Am Ende erhält die teilnehmende Person ein persönliches Kompetenzprofil, mögliche Stärken, Entwicklungsfelder und einen konkreten Entwicklungsimpuls.

## Datenschutz

Die Anwendung ist vollständig statisch.

- Es gibt keine Datenbank.
- Antworten werden nicht an GitHub übertragen.
- Die Auswertung geschieht im Browser.
- Ein Zwischenstand kann optional im lokalen Browser-Speicher abgelegt werden.
- Antworten können freiwillig als JSON-Datei exportiert werden.

Wichtig: Die Website selbst ist bei GitHub Pages öffentlich erreichbar, sofern das Repository bzw. die Pages-Konfiguration öffentlich ist. Deshalb sollten keine personenbezogenen Antwortdateien in das Repository hochgeladen werden.

## Veröffentlichung auf GitHub Pages

1. GitHub-Konto öffnen.
2. Neues Repository anlegen, z. B. `kompetenzcheck-lehrkraefte`.
3. Die Dateien aus diesem Paket hochladen.
4. Im Repository `Settings` öffnen.
5. Links `Pages` auswählen.
6. Unter `Build and deployment` → `Source` die Option `Deploy from a branch` wählen.
7. Branch `main` und Ordner `/(root)` auswählen.
8. Speichern.
9. GitHub zeigt anschließend die Webadresse der veröffentlichten Seite an.

Die für die Website entscheidende Datei heißt `index.html`.

## Anpassung

Texte und Fragen stehen direkt in `index.html`. Für Änderungen kann die Datei erneut erzeugt oder auf GitHub bearbeitet werden.
