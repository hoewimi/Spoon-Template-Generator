# SpoonDraft v36 – Besteck und Facetten

| Version | Name | Datum | Tag |
|---|---|---|---|
| v36 | Besteck und Facetten | 05.11.2026 | `spoon-v36` |

## Ergebnis

SpoonDraft zeichnet jetzt Salatbesteck als Paar (zwei Teile auf einem Blatt, Kopf je Teil Laffe, Gabel, Paddel oder Laffe mit Loch) und hat Spurtle, Kuksa und Streichmesser nach Recherche überarbeitet. Die Facetten der Löffel beginnen jetzt unter der Laffe, die Schablone der vier Löffelarten mit Facetten ändert sich dadurch leicht. Spendenknopf und anonymer Export-Zähler sind eingebaut, in dieser Version aber ausgeschaltet, weil Ko-fi-Name und GoatCounter-Code noch fehlen; die Texte gibt es in 10 Sprachen.

## Neu in dieser Version

### Grundset

| Was | Feature | Stufe |
|---|---|---|
| Spendenknopf und anonymer Export-Zähler (ausgeschaltet, bis Ko-fi-Name und GoatCounter-Code eingetragen sind) | `spende` | grund |
| Facetten beginnen bis 10 mm unter der Laffe, in der Draufsicht gestrichelt | `geometrie` | grund |

### Zusatzfunktionen

| Was | Feature | Stufe |
|---|---|---|
| Spurtle mit Wulst, Kopfwahl und flacher Bauform | `spurtle` | zusatz |
| Kuksa mit drei Schalenformen, Henkel mit Fingermulde und neuen Werkseinstellungen | `kuksa` | zusatz |
| Streichmesser mit mindestens 2 mm dicker Kante | `buttermesser` | zusatz |
| Salatbesteck als Paar | `salatbesteck` | zusatz |
| Besteckkopf „Laffe mit Loch“ mit Nut zur Spitze | `salatbesteck` | zusatz |

### Ohne Feature

| Was | Feature | Stufe |
|---|---|---|
| Release v36 | – | – |

## Alle Features dieser Version

Feature-Kennungen und Stufen aus `FEATURES.md` zum Tag `spoon-v36`.

### Grundset

Immer an: ohne diese Funktionen lässt sich keine Schablone erzeugen, ansehen und speichern.

| Feature | Stufe | Inhalt |
|---|---|---|
| `formen` | grund | Laffen- und Griffendformen, Formvorgaben Ei, Feige, Squoval, Oval, Kennungen L/G, eigene Formen im Browser |
| `geometrie` | grund | Rechnet Laffe, Stiel, Facetten (beginnen unter der Laffe), Seitenprofil und Blatt |
| `export` | grund | Speichern als PDF, SVG und Laser-SVG |
| `spende` | grund | Spendenknopf und anonymer Export-Zähler, ohne Ko-fi-Name und GoatCounter-Code ausgeschaltet |
| `vorschau` | grund | Das Blatt am Bildschirm |
| `zoom` | grund | Zoom und Verschieben, Mini-Übersicht |
| `ansicht3d` | grund | 3D-Ansicht mit drei Darstellungen, Ansichten tauschen, zeichnet nur bei Änderungen |
| `angaben` | grund | Rohling, Absenkung, Papier, Laffenanteil, Warnungen, Drucktipps |
| `loeffelart` | grund | Auswahl der Art (Löffelarten und Zusatzarten) |
| `bedienfeld` | grund | Regler, Auswahlknöpfe, Formgalerien |
| `sprache` | grund | Sprachauswahl (10 Sprachen) |
| `design` | grund | Vier Designs, hell und dunkel |
| `standardwerte` | grund | Fenster ⚙ mit eigenen Standardwerten, Warngrenzen und den Schaltern der Zusatzfunktionen |

### Zusatzfunktionen

Im Fenster ⚙ unter „Zusatzfunktionen“ einzeln abschaltbar.

| Feature | Stufe | Inhalt |
|---|---|---|
| `hinweise` | zusatz | Hinweis zu Faser und Kröpfung beim Seitenprofil |
| `eigene-formen` | zusatz | Form aus Bild hochladen, Formen als Datei teilen |
| `zufall` | zusatz | Zufallsdesign |
| `editor` | zusatz | Formeditor für Laffe und Griffende |
| `meine-loeffel` | zusatz | Entwürfe mit Name, Notiz und Fotos, Sicherung als Datei |
| `wandstaerke` | zusatz | Hilfslinien Mindestwandstärke und Tiefenmarke, nur am Bildschirm |
| `rundgang` | zusatz | Rundgang durch die Oberfläche |
| `stamm` | zusatz | Dialog Stammquerschnitt: wie viele Rohlinge in einen Stamm passen |
| `pfannenwender` | zusatz | Art Pfannenwender mit schrägem oder geradem Blatt und Kröpfung |
| `spurtle` | zusatz | Art Spurtle, rund oder flach, mit Wulst und Kopfwahl |
| `buttermesser` | zusatz | Art Buttermesser, Klingenform Streichmesser oder Schwedisch |
| `salatgabel` | zusatz | Art Salatgabel mit 2 bis 4 Zinken |
| `kuksa` | zusatz | Art Kuksa mit drei Schalenformen, vier Griffvarianten und Fassungsvermögen |
| `salatbesteck` | zusatz | Art Salatbesteck als Paar, Kopf je Teil Laffe, Gabel, Paddel oder Laffe mit Loch |

## Bekannte Grenzen

- Für das PDF braucht die Seite eine Internetverbindung (die PDF-Funktion wird aus dem Internet geladen).
- Eigene Formen werden nur in diesem Browser gespeichert.
- Zu breite Schablonen bleiben bei „2 × A4“ auf A3 (mit Hinweis).
- Bei Polnisch ist die Schablone englisch beschriftet.
- Eigene Standardwerte werden nur in diesem Browser gespeichert.
- Beta: Nutzung ohne Gewähr.
- Entwürfe und Fotos aus „Meine Löffel“ liegen nur in diesem Browser; zum Übertragen dient die Sicherung als Datei. Die Fotos erscheinen nicht im PDF.
- Die Wahl der Zusatzfunktionen gilt nur in diesem Browser.
- Hilfslinien der Mindestwandstärke und die Tiefenmarke stehen nur am Bildschirm, nicht auf der Schablone.
- Der Stammquerschnitt steht nur am Bildschirm, nicht auf der Schablone.
- Die Maße der neuen Arten sind Richtwerte aus handelsüblichen Angaben und Recherche; ob sie für jeden Zweck passen, ist nicht belegt.
- Spendenknopf und Zähler sind in dieser Version ausgeschaltet; ob und wann sie aktiviert werden, ist nicht belegt.
- Das Loch beim Salatbesteck-Kopf „Laffe mit Loch“ zeigt in der 3D-Ansicht bei starkem Zoom auf der Mittellinie eine feine gestrichelte Haarlinie (Tiefenpuffer, kein Spalt).
- Die Kuksa zeigt das Fassungsvermögen trocken bis zum Rand (auf 5 ml gerundet), nicht den Inhalt des fertigen, geölten Gefäßes.
- Die große 3D-Ansicht (⇄) schneidet lange Körper am Rand ab.
- Am Handy überdeckt die feststehende Vorschau den Anfang der ersten Feldgruppe.

Aus `Versionen/UEBERGABE.md` (Stand 29.10.2026, danach nicht nachgeführt; ob jeder Punkt genau für diese Version gilt, ist nicht belegt):

- Bei Länge ab ca. 345 mm mit steilem Crank passt die Zeichnung nicht aufs Blatt und kann das Schriftfeld berühren.
- Die Standard-Schöpfkelle ist zu breit für A4 und bleibt auf A3.
- Kiel unten steht auf der Schablone nur als Text; 3D-Kanten wirken weich.
- Bei `kr = 0` überschneidet sich die Kontur am Knick leicht.
- Formen aus dem Scan sind ungenauer als die Vektorformen.
- Kein Zoom mit zwei Fingern.
- Übersetzungen Norwegisch, Dänisch und Polnisch nicht von Muttersprachlern geprüft.

## Links

- Öffentliche Seite: https://hoewimi.github.io/Spoon-Template-Generator/ (zeigt immer nur die neueste Version)
