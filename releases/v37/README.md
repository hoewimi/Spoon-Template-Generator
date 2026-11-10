# SpoonDraft v37 – Klingen und Stiele

| Version | Name | Datum | Tag |
|---|---|---|---|
| v37 | Klingen und Stiele | 06.11.2026 | `spoon-v37` |

## Ergebnis

Das Buttermesser hat vier neue Klingenformen, eine wählbare Griffform und eine Klinge, die du selbst im Formeditor entwirfst. Pfannenwender und Salatbesteck bekommen den vollen Stiel mit Facetten wie der Löffel, und im Laser-SVG zerfällt die Schablone nicht mehr an den Mittellinien (außer bei der Kuksa). Die Seite lädt ihre Schriften nicht mehr von Google, nennt im neuen Über-Dialog Lizenzen, Datenschutz und Impressum und steht unter der ISC-Lizenz; der Spendenknopf ist eingeschaltet.

## Neu in dieser Version

### Grundset

| Was | Feature | Stufe |
|---|---|---|
| Laser-SVG: Mittellinien nur noch als kurze Marken innerhalb des Umrisses, außer bei der Kuksa | `export` | grund |
| Dialog Über mit Version, Lizenzen und Datenschutzhinweisen, Schriften in der Datei statt von Google, ISC-Lizenz | `ueber` | grund |
| Spendenknopf eingeschaltet, der anonyme Zähler bleibt aus | `spende` | grund |
| Impressum im Dialog Über | `ueber` | grund |

### Zusatzfunktionen

| Was | Feature | Stufe |
|---|---|---|
| Voller Stiel am Pfannenwender: Facetten, Kiel, Stielstärke, Verdickung am Hals, Lage der größten Griffbreite | `pfannenwender` | zusatz |
| Neue Klingenformen Blatt, Spatel, Breit und Geschwungen, Griffform gerade, ausgestellt oder bauchig | `buttermesser` | zusatz |
| Salatbesteck mit Stiel, Facetten, Knickübergang, Stielkrümmung, Händigkeit und Wandstärke wie beim Löffel | `salatbesteck` | zusatz |
| Buttermesser-Klinge im Formeditor selbst entwerfen und speichern | `editor` | zusatz |
| Griff der Kuksa mit zwei Löchern schließt bündig mit dem Rand ab | `kuksa` | zusatz |

### Ohne Feature

| Was | Feature | Stufe |
|---|---|---|
| Release v37 | – | – |

## Alle Features dieser Version

Feature-Kennungen und Stufen aus `FEATURES.md` zum Tag `spoon-v37`.

### Grundset

Immer an: ohne diese Funktionen lässt sich keine Schablone erzeugen, ansehen und speichern.

| Feature | Stufe | Inhalt |
|---|---|---|
| `formen` | grund | Laffen- und Griffendformen, Formvorgaben Ei, Feige, Squoval, Oval, Kennungen L/G, eigene Formen im Browser |
| `geometrie` | grund | Rechnet Laffe, Stiel, Facetten (beginnen unter der Laffe), Seitenprofil und Blatt |
| `export` | grund | Speichern als PDF, SVG und Laser-SVG, im Laser-SVG Mittellinien als Marken (außer Kuksa) |
| `spende` | grund | Spendenknopf eingeschaltet, anonymer Export-Zähler eingebaut, aber ausgeschaltet |
| `vorschau` | grund | Das Blatt am Bildschirm |
| `zoom` | grund | Zoom und Verschieben, Mini-Übersicht |
| `ansicht3d` | grund | 3D-Ansicht mit drei Darstellungen, Ansichten tauschen, zeichnet nur bei Änderungen |
| `angaben` | grund | Rohling, Absenkung, Papier, Laffenanteil, Warnungen, Drucktipps |
| `loeffelart` | grund | Auswahl der Art (Löffelarten und Zusatzarten) |
| `bedienfeld` | grund | Regler, Auswahlknöpfe, Formgalerien |
| `sprache` | grund | Sprachauswahl (10 Sprachen) |
| `design` | grund | Vier Designs, hell und dunkel |
| `standardwerte` | grund | Fenster ⚙ mit eigenen Standardwerten, Warngrenzen und den Schaltern der Zusatzfunktionen |
| `ueber` | grund | Dialog Über mit Version, Lizenzen, Datenschutzhinweisen und Impressum |

### Zusatzfunktionen

Im Fenster ⚙ unter „Zusatzfunktionen“ einzeln abschaltbar.

| Feature | Stufe | Inhalt |
|---|---|---|
| `hinweise` | zusatz | Hinweis zu Faser und Kröpfung beim Seitenprofil |
| `eigene-formen` | zusatz | Form aus Bild hochladen, Formen als Datei teilen |
| `zufall` | zusatz | Zufallsdesign |
| `editor` | zusatz | Formeditor für Laffe, Griffende und Buttermesser-Klinge |
| `meine-loeffel` | zusatz | Entwürfe mit Name, Notiz und Fotos, Sicherung als Datei |
| `wandstaerke` | zusatz | Hilfslinien Mindestwandstärke und Tiefenmarke, nur am Bildschirm |
| `rundgang` | zusatz | Rundgang durch die Oberfläche |
| `stamm` | zusatz | Dialog Stammquerschnitt: wie viele Rohlinge in einen Stamm passen |
| `pfannenwender` | zusatz | Art Pfannenwender mit schrägem oder geradem Blatt, Kröpfung und vollem Stiel wie beim Löffel |
| `spurtle` | zusatz | Art Spurtle, rund oder flach, mit Wulst und Kopfwahl |
| `buttermesser` | zusatz | Art Buttermesser mit sechs Klingenformen, eigener Klinge und drei Griffformen |
| `salatgabel` | zusatz | Art Salatgabel mit 2 bis 4 Zinken |
| `kuksa` | zusatz | Art Kuksa mit drei Schalenformen, vier Griffvarianten und Fassungsvermögen |
| `salatbesteck` | zusatz | Art Salatbesteck als Paar, Kopf je Teil Laffe, Gabel, Paddel oder Laffe mit Loch, Stiel und Facetten wie beim Löffel |

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
- Das Loch beim Salatbesteck-Kopf „Laffe mit Loch“ zeigt in der 3D-Ansicht bei starkem Zoom auf der Mittellinie eine feine gestrichelte Haarlinie (Tiefenpuffer, kein Spalt).
- Bei der Kuksa bleiben die Mittellinien im Laser-SVG durchgehend und können die Schablone beim Lasern zerteilen.
- Im Laser-SVG kreuzen Facetten-, Knick- und Bezugslinien im Seitenprofil die Schnittkontur (am Esslöffel gesehen).
- Der Griff der Kuksa mit zwei Löchern hängt ab Werk 24 mm unter dem Boden; die Schale steht dann nicht mehr (Hinweis im Schriftfeld).
- Die Datenschutzhinweise und das Impressum gibt es nur auf Deutsch und Englisch.
- Der Zähler ist in dieser Version ausgeschaltet; ob und wann er aktiviert wird, ist nicht belegt.
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
