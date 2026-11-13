# SpoonDraft v39 – Facetten für alle

| Version | Name | Datum | Tag |
|---|---|---|---|
| v39 | Facetten für alle | 13.11.2026 | `spoon-v39` |

## Ergebnis

Die Facetten laufen bei allen Arten mit Stiel gleich und weich in den Kopf aus; Salatgabel und Buttermesser haben jetzt Facetten wie der Löffel (ab Werk aus). Beim Buttermesser wählst du die Spitze: abgerundet oder leicht spitz. Bei Salatgabel und Salatbesteck geht der Stiel weich in den Kopf über, wie beim Löffel. Die Knöpfe „Support me on Ko-fi“ entfallen, das Herz bleibt, und der Schatten der 3D-Ansicht ist heller.

## Neu in dieser Version

### Grundset

| Was | Feature | Stufe |
|---|---|---|
| Facetten: Die Fase wächst am Übergang zum Kopf stetig und weich an und läuft einheitlich in den Auslauf zum Griff über, bei allen Arten mit Stiel; der Pfannenwender folgt derselben Regel wie die Löffel | `geometrie` | grund |
| Knopf „Support me on Ko-fi“ mit Schriftzug aus Fußzeile und Über-Dialog entfernt, das Herz bleibt | `spende` | grund |

### Zusatzfunktionen

| Was | Feature | Stufe |
|---|---|---|
| Buttermesser-Spitze wählbar: abgerundet oder leicht spitz | `buttermesser` | zusatz |
| Buttermesser: Facetten am Griff wie beim Löffel, ab Werk aus | `buttermesser` | zusatz |
| Salatgabel und Salatbesteck: weicher Übergang vom Stiel zum Kopf wie beim Esslöffel | `salatgabel` | zusatz |
| Salatgabel: Facetten wie beim Löffel, ab Werk aus | `salatgabel` | zusatz |

### Ohne Feature

| Was | Feature | Stufe |
|---|---|---|
| Schatten unter dem Löffel in der 3D-Ansicht etwa halb so dunkel | – | – |
| Code-Review Teil 1 (Kern, Rechnen, Export): nur ein Bericht, kein Code | – | – |
| Code-Review Teil 2 (Arten): nur ein Bericht, kein Code | – | – |
| Release v39 | – | – |

## Alle Features dieser Version

Feature-Kennungen und Stufen aus `FEATURES.md` zum Tag `spoon-v39`.

### Grundset

Immer an: ohne diese Funktionen lässt sich keine Schablone erzeugen, ansehen und speichern.

| Feature | Stufe | Inhalt |
|---|---|---|
| `formen` | grund | Laffen- und Griffendformen, Formvorgaben Ei, Feige, Squoval, Oval, Kennungen L/G/K/W/M, eigene Formen im Browser |
| `geometrie` | grund | Rechnet Laffe, Stiel, Facetten (einstellbare Breite, beginnen unter der Laffe, bei allen Arten mit Stiel gleiche weiche Regel am Übergang zum Kopf), Seitenprofil mit glatter Laffe und Blatt |
| `export` | grund | Speichern als PDF, SVG und Laser-SVG, im Laser-SVG Umriss rot geschnitten, Linien innen blau graviert |
| `spende` | grund | Spendenknopf (Herz), kein Knopf mit Schriftzug mehr; anonymer Export-Zähler eingebaut, aber ausgeschaltet |
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
| `pfannenwender` | zusatz | Art Pfannenwender mit schrägem oder geradem Blatt, Blatt als Freiform, Kröpfung und vollem Stiel mit Facetten bis ins Blatt (am Übergang dieselbe weiche Regel wie bei den Löffeln) |
| `spurtle` | zusatz | Art Spurtle, rund oder flach, mit Wulst und Kopfwahl |
| `buttermesser` | zusatz | Art Buttermesser mit sechs Klingenformen, wählbarer Spitze (abgerundet oder leicht spitz), eigener Klinge, ganzem Messer als Freiform, drei Griffformen und Facetten am Griff |
| `salatgabel` | zusatz | Art Salatgabel mit 2 bis 4 Zinken, weichem Übergang vom Stiel zum Kopf und Facetten wie beim Löffel |
| `kuksa` | zusatz | Art Kuksa mit drei Schalenformen, vier Griffvarianten und Fassungsvermögen |
| `salatbesteck` | zusatz | Art Salatbesteck als Paar, Kopf je Teil Laffe, Gabel, Paddel oder Laffe mit Loch, Stiel und Facetten wie beim Löffel, weicher Übergang vom Stiel zum Kopf |

## Bekannte Grenzen

- Bei den vier Löffelarten ist die Fase am kurzen Hals mit Facetten bis zu 0,8 mm schmaler als in v38 (Beispiel Kochlöffel mit eigener Facettenbreite 60 %: 4,24 statt 5,05 mm); der Auslauf zum Griff beginnt später und ist kürzer, auch beim Bereich „Stiel“ (5 bis 23 mm später). Die größte Fasenbreite wird nie größer als in v38; im späteren, kürzeren Auslauf zum Griff ist die Fase dafür stellenweise breiter als vorher an derselben Stelle (Faktor 1,06 bis 1,56, größter Unterschied 1,9 mm bei der Schöpfkelle mit eigener Facettenbreite 60 % am Hals). Ohne Facetten bleibt die Schablone gleich.
- Buttermesser: Bei kurzem Griff und langer Klinge knickt die Fasenkante in der 3D-Darstellung „Technisch“ um mehr als 30° (gemessen bis 45,2°, bei Länge 100 bis 120 mm mit Klinge 200 %); ab Länge 140 mm bleibt sie darunter.
- Buttermesser: Bei Fasenbreiten über 30 % springt die Fasenbreite im Auslauf zum Griff stärker als bei den Löffeln (gemessen bis 0,081 mm bei 60 %, bei den Löffeln mit dickem Stiel bis 0,086 mm).
- Buttermesser: Die Gruppe mit den Facettenreglern heißt „Stiel“; auf Englisch, Französisch, Spanisch und Italienisch trägt sie denselben Namen wie die Gruppe „Griff“ (zum Beispiel zweimal „Handle“).
- Salatbesteck: Bei den Vorgabewerten ist der Rohling der Laffe 28 statt 29 mm hoch, weil der Kopf am Ende dicker ist und die Mulde dadurch höher liegt.
- Salatbesteck und Salatgabel: Bei sehr enger Kröpfung knickt die Innenseite; bei einem Zufallssatz (kurze Laffe, dicker Stiel, Stielverdickung 50 %) knickt der Querschnitt am Kopfende um 31,9° statt höchstens 30°.
- Salatbesteck: Die Rechenzeit der 3D-Ansicht liegt rund 13 % höher als in v38 (für die Salatgabel nicht belegt).
- Salatgabel: Bei dickem Stiel oder kurzer Gabel knickt die obere Fasenkante gleich unter dem Gabelkopf (gemessen 33,5° und 36,6°, in Zufallssätzen bis 49,2°).
- Salatbesteck: Die Mulde der Laffe weicht in den letzten 3 mm vor dem Kopfende leicht ab (an den Netzpunkten höchstens 0,26 mm, an der steilen Wand einer 16,7 mm tiefen Mulde bis 2,23 mm).
- In der 3D-Ansicht wölbt sich der Streifen der Seitenwand zwischen oberer und unterer Fase am Übergang vom Kopf zum Stiel aus und ist dort breiter als in v38, deutlich beim Pfannenwender, schwächer beim Salatbesteck und als leichte Auswölbung des Stielumrisses beim Kochlöffel; bei Esslöffel, Kaffeelöffel und Schöpfkelle ist sie nicht zu sehen. Die Draufsicht ist gleich; Ursache ist der spätere Auslauf zum Griff (Pfannenwender 100,0 statt 108,3 mm, Salatbesteck 100,0 statt 109,9 mm, Kochlöffel 70,0 statt 85,6 mm).
- Im Impressum und in den Datenschutzhinweisen stehen noch die Platzhalter [KONTAKT-E-MAIL], [WEITERER KONTAKTWEG], [SPEICHERFRIST] und [DATUM DER PRÜFUNG]; die Kontaktangaben sind also noch nicht veröffentlicht.
- Impressum und Datenschutzhinweise sind eine Arbeitsvorlage und nicht rechtlich geprüft (so im Text vermerkt); sie gibt es nur auf Deutsch und Englisch.
- „Laffe glätten“ gilt für die Löffelarten; das Salatbesteck bleibt unverändert, gespeicherte Entwürfe ohne den Schalter laden mit „An“. Außerhalb der 124 Werkseinstellungen können größte Tiefe und tiefste Stelle leicht abweichen, und der Boden unter der Mulde wird bei Kellen bis 1 mm dünner (nie unter 3 mm).
- Im Laser-SVG fehlen Texte, Füllungen, Prüfbalken, Maßpfeile, Schriftfeld sowie Anlegelinien und Passkreuze von 2 × A4, Reststücke unter 0,5 mm entfallen, und die Gravur reicht bis an den Umriss: Eine zu tiefe Gravur lässt die Schablone beim Lasern zerfallen.
- Beim Salatbesteck gelten eine eigene Laffe und ein Griffende für beide Teile; getrennte Formen je Teil gibt es nicht.
- Das Pfannenwender-Blatt ist auf 140 mm Breite begrenzt, das ganze Buttermesser auf 60 mm (Hinweis im Schriftfeld); ein ganzes Messer lässt sich nicht aus einem Bild anlegen.
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
