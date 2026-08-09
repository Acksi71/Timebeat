TIMEBEAT ULTRA v8.13 – GitHub/iPhone Fix

WAS WURDE BEHOBEN?
- Das Startformular steht direkt im HTML.
- Alle Event-Handler werden erst nach DOMContentLoaded gesetzt.
- Der Fehler, der JavaScript vor der Startinitialisierung abgebrochen hat, ist beseitigt.
- PWA-Cache wurde auf v8.13 geändert.

UPLOAD:
Diese Dateien im GitHub-Repository ersetzen/hochladen:
index.html
manifest.webmanifest
sw.js
.nojekyll
icon-192.png
icon-512.png

Danach GitHub Pages kurz neu deployen lassen.

IPHONE:
Zum ersten Test in Safari unbedingt öffnen:
https://acksi71.github.io/Timebeat/?v=813

Wenn unten rechts "v8.13" steht, ist sicher die neue Datei geladen.
Danach kann die alte Home-Screen-Version gelöscht und neu zum Home-Bildschirm hinzugefügt werden.
