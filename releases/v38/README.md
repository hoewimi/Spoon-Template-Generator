# SpoonDraft v38 – Freiformen und Facetten

| Version | Name | Datum | Tag |
|---|---|---|---|
| v38 | Freiformen und Facetten | 10.11.2026 | `spoon-v38` |

## Ergebnis

Im Formeditor zeichnest du jetzt Laffe, Griffende, Pfannenwender-Blatt und ganze Buttermesser frei, mit Millimeterraster, Einrasten und bis zu 32 Punkten je Hälfte; eigene Formen gibt es bei allen Arten mit Laffe oder Griffende. Die Breite der Facetten stellst du in Schritten von 1 % ein, und die Unterseite der Laffe läuft im Seitenprofil ohne Knicke und in 3D deutlich glatter (Schalter „Laffe glätten“). Das Laser-SVG zeigt dieselbe Zeichnung wie das SVG, abgeschnitten am Umriss; PDF-Export und 3D-Ansicht laden nichts mehr aus dem Internet, und in der Fußzeile stehen Impressum, Datenschutz und Lizenzen.

## Neu in dieser Version

### Grundset

| Was | Feature | Stufe |
|---|---|---|
| Laser-SVG wie das SVG, je Ansicht an der Außenlinie abgeschnitten: Umriss rot geschnitten, die Linien innerhalb des Umrisses blau graviert, Mittellinien durchgehend | `export` | grund |
| Fußzeile mit Impressum, Datenschutz, Lizenz und Drittanbieter-Lizenzen, Texte nach den belegten Datenflüssen | `ueber` | grund |
| Knopf „Support me on Ko-fi“ mit Schriftzug in Fußzeile und Über-Dialog | `spende` | grund |
| Facettenbreite einstellbar, 10 bis 60 %, „Leicht“ und „Achteckig“ als Schnellwahl | `geometrie` | grund |
| Laffe außen glatt in Seitenprofil und 3D, Schalter „Laffe glätten“ (ab Werk an) | `geometrie` | grund |

### Zusatzfunktionen

| Was | Feature | Stufe |
|---|---|---|
| Raster im Formeditor, Punkte rasten am Raster ein | `editor` | zusatz |
| Facetten des Pfannenwenders laufen bis ins Blatt | `pfannenwender` | zusatz |
| Eigene Formen für alle Arten mit Laffe oder Griffende (Salatgabel, Salatbesteck, Pfannenwender, Spurtle) | `editor` | zusatz |
| Pfannenwender-Blatt als Freiform | `pfannenwender` | zusatz |
| Ganzes Buttermesser als Freiform | `buttermesser` | zusatz |
| Knöpfe „Punkt einfügen“ und „Punkt löschen“, Punktanzeige, bis 32 Punkte je Hälfte | `editor` | zusatz |

### Ohne Feature

| Was | Feature | Stufe |
|---|---|---|
| jsPDF und three.js stecken in der Datei, kein Zugriff mehr auf cdnjs | – | – |
| Release v38 | – | – |

## Alle Features dieser Version

Feature-Kennungen und Stufen aus `FEATURES.md` zum Tag `spoon-v38`.

### Grundset

Immer an: ohne diese Funktionen lässt sich keine Schablone erzeugen, ansehen und speichern.

| Feature | Stufe | Inhalt |
|---|---|---|
| `formen` | grund | Laffen- und Griffendformen, Formvorgaben Ei, Feige, Squoval, Oval, Kennungen L/G/K/W/M, eigene Formen im Browser |
| `geometrie` | grund | Rechnet Laffe, Stiel, Facetten (einstellbare Breite, beginnen unter der Laffe), Seitenprofil mit glatter Laffe und Blatt |
| `export` | grund | Speichern als PDF, SVG und Laser-SVG, im Laser-SVG Umriss rot geschnitten, Linien innen blau graviert |
| `spende` | grund | Spendenknopf (Herz) und Knopf „Support me on Ko-fi“, anonymer Export-Zähler eingebaut, aber ausgeschaltet |
| `vorschau` | grund | Das Blatt am Bildschirm |
| `zoom` | grund | Zoom und Verschieben, Mini-Übersicht |
| `ansicht3d` | grund | 3D-Ansicht mit drei Darstellungen, Ansichten tauschen, zeichnet nur bei Änderungen |
| `angaben` | grund | Rohling, Absenkung, Papier, Laffenanteil, Warnungen, Drucktipps |
| `loeffelart` | grund | Auswahl der Art (Löffelarten und Zusatzarten) |
| `bedienfeld` | grund | Regler, Auswahlknöpfe, Formgalerien |
| `sprache` | grund | Sprachauswahl (10 Sprachen) |
| `design` | grund | Vier Designs, hell und dunkel |
| `standardwerte` | grund | Fenster ⚙ mit eigenen Standardwerten, Warngrenzen und den Schaltern der Zusatzfunktionen |
| `ueber` | grund | Dialog Über und Fußzeile mit Version, Lizenzen, Datenschutzhinweisen und Impressum |

### Zusatzfunktionen

Im Fenster ⚙ unter „Zusatzfunktionen“ einzeln abschaltbar.

| Feature | Stufe | Inhalt |
|---|---|---|
| `hinweise` | zusatz | Hinweis zu Faser und Kröpfung beim Seitenprofil |
| `eigene-formen` | zusatz | Form aus Bild hochladen, Formen als Datei teilen |
| `zufall` | zusatz | Zufallsdesign |
| `editor` | zusatz | Formeditor für Laffe, Griffende, Buttermesser-Klinge, ganzes Buttermesser und Pfannenwender-Blatt mit Raster, Einrasten und bis zu 32 Punkten je Hälfte |
| `meine-loeffel` | zusatz | Entwürfe mit Name, Notiz und Fotos, Sicherung als Datei |
| `wandstaerke` | zusatz | Hilfslinien Mindestwandstärke und Tiefenmarke, nur am Bildschirm |
| `rundgang` | zusatz | Rundgang durch die Oberfläche |
| `stamm` | zusatz | Dialog Stammquerschnitt: wie viele Rohlinge in einen Stamm passen |
| `pfannenwender` | zusatz | Art Pfannenwender mit schrägem oder geradem Blatt, Blatt als Freiform, Kröpfung und vollem Stiel mit Facetten bis ins Blatt |
| `spurtle` | zusatz | Art Spurtle, rund oder flach, mit Wulst und Kopfwahl |
| `buttermesser` | zusatz | Art Buttermesser mit sechs Klingenformen, eigener Klinge, ganzem Messer als Freiform und drei Griffformen |
| `salatgabel` | zusatz | Art Salatgabel mit 2 bis 4 Zinken |
| `kuksa` | zusatz | Art Kuksa mit drei Schalenformen, vier Griffvarianten und Fassungsvermögen |
| `salatbesteck` | zusatz | Art Salatbesteck als Paar, Kopf je Teil Laffe, Gabel, Paddel oder Laffe mit Loch, Stiel und Facetten wie beim Löffel |

## Bekannte Grenzen

- Die Schablone der vier Löffelarten ändert sich gegenüber v37 im Seitenprofil (glatte Unterseite der Laffe); mit „Laffe glätten“ auf „Aus“ ist sie zeichengleich zu v37. Die Draufsicht rückt dabei höchstens 0,06 mm zur Seite, und bei 10 von 124 Werkseinstellungen aus Laffenformen und Löffelarten ändert sich ein gerundetes Rohlingmaß um 1 mm.
- Mit „Laffe glätten“ an fehlt bei der Schöpfkelle in der 3D-Darstellung „Technisch“ das erste, rund 3,7 mm lange Stück der Facettenkante am Beginn der Fase.
- Im Impressum und in den Datenschutzhinweisen stehen noch die Platzhalter [KONTAKT-E-MAIL], [WEITERER KONTAKTWEG], [SPEICHERFRIST] und [DATUM DER PRÜFUNG]; die Kontaktangaben sind also noch nicht veröffentlicht.
- „Laffe glätten“ gilt für die Löffelarten; das Salatbesteck bleibt unverändert, gespeicherte Entwürfe ohne den Schalter laden mit „An“. Außerhalb der 124 Werkseinstellungen können größte Tiefe und tiefste Stelle leicht abweichen, und der Boden unter der Mulde wird bei Kellen bis 1 mm dünner (nie unter 3 mm).
- Im Laser-SVG fehlen Texte, Füllungen, Prüfbalken, Maßpfeile, Schriftfeld sowie Anlegelinien und Passkreuze von 2 × A4, Reststücke unter 0,5 mm entfallen, und die Gravur reicht bis an den Umriss: Eine zu tiefe Gravur lässt die Schablone beim Lasern zerfallen.
- Beim Salatbesteck gelten eine eigene Laffe und ein Griffende für beide Teile; getrennte Formen je Teil gibt es nicht.
- Das Pfannenwender-Blatt ist auf 140 mm Breite begrenzt, das ganze Buttermesser auf 60 mm (Hinweis im Schriftfeld); ein ganzes Messer lässt sich nicht aus einem Bild anlegen.
- Der Knopf „Support me on Ko-fi“ (Weiß auf `#72a4f2`) erreicht nur einen Kontrast von 2,53:1, unter den geforderten 4,5:1.
- Impressum und Datenschutzhinweise sind eine Arbeitsvorlage und nicht rechtlich geprüft (so im Text vermerkt); sie gibt es nur auf Deutsch und Englisch.
- Eigene Formen werden nur in diesem Browser gespeichert.
- Zu breite Schablonen bleiben bei „2 × A4“ auf A3 (mit Hinweis).
- Bei Polnisch ist die Schablone englisch beschriftet.
- Eigene Standardwerte werden nur in diesem Browser gespeichert.
- Beta: Nutzung ohne Gewähr.
- Entwürfe und Fotos aus „Meine Löffel“ liegen nur in diesem Browser; zum Übertragen dient die Sicherung als Datei. Die Fotos erscheinen nicht im PDF.
- Die Wahl der Zusatzfunktionen gilt nur in diesem Browser.
- Hilfslinien der Mindestwandstärke, die Tiefenmarke, der Stammquerschnitt und das Raster im Formeditor stehen nur am Bildschirm, nicht auf der Schablone.
- Die Maße der neuen Arten sind Richtwerte aus handelsüblichen Angaben und Recherche; ob sie für jeden Zweck passen, ist nicht belegt.
- Das Loch beim Salatbesteck-Kopf „Laffe mit Loch“ zeigt in der 3D-Ansicht bei starkem Zoom auf der Mittellinie eine feine gestrichelte Haarlinie (Tiefenpuffer, kein Spalt).
- Der Griff der Kuksa mit zwei Löchern hängt ab Werk 24 mm unter dem Boden; die Schale steht dann nicht mehr (Hinweis im Schriftfeld).
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
