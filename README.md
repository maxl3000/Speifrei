# 🤮 Speifrei

Eine kleine Timer-Web-App für die wichtigste Bestenliste unter Freunden:
**Wer hat am längsten nicht gekotzt?**

Jede Person bekommt ein Datum („zuletzt gekotzt am“) und einen live laufenden Timer.
Die Liste sortiert automatisch: längste Zeit oben (👑 Speifrei-König), kürzeste unten
(🤮 zuletzt gekotzt).

## Features

- Personen mit Name und Datum/Uhrzeit anlegen, bearbeiten, löschen
- Live-Timer pro Person (Tage + hh:mm:ss)
- Automatische Rangliste mit Medaillen, König-Badge und „Zuletzt gekotzt“-Markierung
- Button „🤮 Gerade gekotzt!“ setzt den Timer auf jetzt zurück und zählt das Ereignis
- Persönlicher Rekord (längste Durststrecke) pro Person, inkl. „Rekord läuft“-Badge
- Zähler, wie oft jede Person schon gekotzt hat, plus Gruppen-Gesamtstand
- Daten bleiben im Browser (localStorage)
- **Liste teilen**: erzeugt einen Link, der den kompletten Stand enthält, damit Freunde
  dieselbe Tabelle sehen können
- Export/Import als JSON
- Mobil-optimiert, dunkles Design, kein Build, keine Abhängigkeiten

## Benutzen

Einfach `index.html` im Browser öffnen. Fertig.

### Online stellen (GitHub Pages)

1. Im Repo unter **Settings → Pages** als Source „Deploy from a branch“ wählen
2. Branch `main` (oder den gewünschten Branch), Ordner `/ (root)`
3. Die App ist danach unter `https://<user>.github.io/Speifrei/` erreichbar

## Hinweis zum Teilen

Es gibt keinen Server. Der Share-Link enthält den Stand zum Zeitpunkt des Teilens.
Wenn jemand seinen Timer zurücksetzt, muss der neue Link erneut geteilt werden.
