## Allgeimenes und Hinweise

txAdmin übersetzt in die Deutsche Sprache.

Dieser Release ist noch **nicht** final. Weitere Übersetzungen und Updates kommen noch.

Bitte fertige ein Backup an, falls diese Version **_nicht_** kompatibel ist!

## Installation
1. Lade die .zip, .rar, .7z oder .tar Datei herunter
2. Öffne die Datei und überschreibe den alpine Ordner
3. Starte den Server neu (nicht den txAdmin Server)

## Was geändert wurde

- Vieles wurde auf Deutsch übersetzt
- MasterActions wurde ausgeblendet (trotzdem weiterhin verfügbar unter der URL: /masterActions)
- Ein kleines Notizen-Feld im Dashboard (Notizen sind nur für einen selbst einsehbar und NICHT Geräte übergreifend.)
- Live-Konsole kann man nicht mehr leeren und es können nun 14 statt 12 Befehle gespeichert werden
- Server Logs kann man nicht mehr löschen
- Eine kleine Veränderung der Ordnung im Linken Bereich
- Der Login Screen wurde verändert
- Das Limit bei "Letzte 25 Aktionen" & "Letzte 30 verbundene Spieler" wurde auf 40 gesetzt.
- Eins / zwei kleinere Änderungen


## Folgende Seiten sind schon vollständig übersetzt
- Login Screen
- 404 Seite
- Live Konsole
- Ressourcen
- Server Logs
- CFG Editor
- Admin Manager
- System Logs

## Fehlerbehebung
Falls keine Spieler, Daten usw. laden, kann die "header.ejs" ausgetauscht werden, dann sollte es wieder gehen.
Diese findest du unter diesem Pfad: deinserver/alpine/opt/cfx-server/citizen/system_resources/monitor/web/parts
(**Hinweis:** Dadurch wird die Leiste ganz links und die Übersetzung der Spieler anzeige rechts, zurückgesetzt)

**ODER / UND**

Falls der Server nicht einwandfrei funktioniert, kannst du die bereitgelegte index.js Datei im folgenden Pfad ersetzten:
txData/alpine/opt/cfx-server/citizen/system_resources/monitor/core/


## Sonstiges
Außerdem kann man bei Bedarf die Logos ersetzten. 
Diese findest du in diesem Pfad: deinserver/alpine/opt/cfx-server/citizen/system_resources/monitor/web/public/img



## Bilder
![Bild_2023-09-06_173944125](https://github.com/Manu06DE/txAdmin-German/assets/109236239/5e96b69d-24cc-4895-a58a-b9a3080f8e9c)
![Bild_2023-09-06_174011576](https://github.com/Manu06DE/txAdmin-German/assets/109236239/c0fa31d5-abab-41c1-85bf-e84490266c6f)
![Bild_2023-09-10_220559697](https://github.com/Manu06DE/txAdmin-reworked/assets/109236239/dde0d5b9-76f1-4a60-9e77-dd190a404180)
![Bild_2023-09-10_220706128](https://github.com/Manu06DE/txAdmin-reworked/assets/109236239/e39ebf63-c257-4e6b-ae52-32b577d73e9e)
![image](https://github.com/Manu06DE/txAdmin-reworked/assets/109236239/83b598bc-a78b-4614-a49d-ecdabc53949f)
![image](https://github.com/Manu06DE/txAdmin-reworked/assets/109236239/c40a04c3-45f4-4963-a0c3-2866a6699fa1)
