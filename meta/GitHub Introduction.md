# Git und Github
## eine Übersicht
---
## Disclaimer 
Ich nutze die englischen Worte für alles was mit git zu tun hat. Bitte verzeiht die daraus entstehenden Satzstrukturen.

---
## Was ist Git?
- Open Source Software für Versionskontrolle
- Ermöglicht auch nicht-lineare Entwicklung
- Lokal, jeder Benutzer hat einer Kopie der gesamten Versionsgeschichte
	-> deshalb: keine Binärdateien mit Git verwalten (pdf, xlsx, accdb, ... ) 
- Komplett Offline

---
### Git für Windows
- Übers Serviceportal beantragbar
- keine UI dabei - aber funktioniert mit Powershell oder Eingabeaufforderung
![[Pasted image 20260317111730.png|257]]

---
## Was ist GitHub?
- Cloud Plattform zum Managen, Verwalten und Teilen von Git *Repositories*[^1]

- Fokus: Zusammenarbeit erleichtern

- Ein *Repository* in GitHub wird als *remote Repository*[^2] bezeichnet



--- 
#### Arbeitsmodus mit Git und GitHub: 
- Lokal Änderungen vornehmen und mit Git tracken

- Lokale Änderungen auf GitHub *pushen*[^3] und veröffentlichen
--- 
## Von Remote zu Lokal
- Eine lokale Kopie von einem *remote Repo* zu erstellen heißt *clone*[^4]

- am einfachsten: in VS Code über die UI 
---
### Aufgabe: Ein Repo *klonen*
Option A: In VS Code über die UI, zb auf der Startseite

Option B: über die command line 
	`git clone <url>`

--- 
## Wie genau funktioniert das?

Zeit für eine Demonstration!

--- 
### Zusammengefasst
- Änderungen vornehmen
- Änderungen *stagen*[^5], also git über die Änderungen informieren
	- `git add <file>` für ein file 
	- ` git add . ` für alle
- Änderungen *committen*[^6]
	- `git commit -m "hier steht meine commit message"`
- Optional: Änderungen *pushen*
	- `git push` 
--- 
### Und jetzt?
Das Repo was ihr geklont habt, hat sich verändert. Mit 
	`git pull`
könnt ihr es wieder auf den neusten Stand bringen

---
## Nicht Lineares Zusammenarbeiten
Über *branches*
![[Pasted image 20260318124645.png]]

---
### Einen *Branch* erstellen 

---
# Zeit für die Aufgaben! 
in Aufgaben.md, wir üben das alles 

---
# Ressourcen
Üben mit Github umzugehen: [skills/introduction-to-github: Get started using GitHub in less than an hour.](https://github.com/skills/introduction-to-github)

---
[^1]: *Repository:* auch "Repo". Projektordner, in dem all deine Dateien gespeichert werden. Merkt sich jede Änderung, die jemals daran vorgenommen wurde.
[^2]: *remote Repository:* "entferntes" Repository, gehostete Version eines Projekts
[^3]:  *push:* Ein lokales Repository auf ein remote Repository "schieben"
[^4]: *clone:* eine lokale Kopie von einem remote Repo erstellen
[^5]: *stage:* git über Änderungen informieren (notwendig vor commit)
[^6]: *commit:* Ein Schnappschuss deines Projekts zu einem bestimmten Zeitpunkt

