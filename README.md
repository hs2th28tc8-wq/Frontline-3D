# Frontline 3D

Ein kostenloses 3D-Browser-Spiel mit lokaler Einzelspieler-Version.

## Starten

- `index.html` im Browser öffnen, oder
- dieses Repository über **Settings → Pages** als GitHub Pages veröffentlichen.
- Als Quelle `Deploy from a branch`, Branch `main` und Ordner `/ (root)` auswählen.

## Steuerung

- **PC:** WASD bewegen, Maus zielen, Linksklick schießen, Rechtsklick zielen, R nachladen, E oder 1–6 Waffen wechseln.
- **Mobil/iPad:** Touch-Joystick und Aktionsknöpfe im Spiel.

## Hinweise

- Der Fortschritt wird lokal im Browser (`localStorage`) gespeichert. Browserdaten löschen oder ein anderes Gerät verwenden bedeutet daher einen anderen lokalen Spielstand.
- Die GitHub-Pages-Version ist ein Offline-/Einzelspieler-Build. Die frühere Claude-Lobby, Freundesliste, Online-Partien sowie Voice-/Text-Chat sind hier nicht aktiv. Für echte Online-Funktionen wäre ein eigener Server mit sicherer Anmeldung und Signalisierung nötig.
- Three.js r128 und die Postprocessing-Skripte werden über CDNs geladen. Zum Spielen ist daher eine Internetverbindung erforderlich.
- Das Projekt wurde für moderne Browser mit WebGL entwickelt.

## Projektstruktur

- `index.html` – das Spiel
- `README.md` – diese Anleitung

## Teststatus

Der JavaScript-Code wurde auf Syntaxfehler geprüft. Ein vollständiger Test auf allen iPads, PCs und Browsern ist damit nicht ersetzt; bitte vor einer öffentlichen Vorstellung selbst kurz im Zielbrowser testen.
