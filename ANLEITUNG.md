# SpoonDraft – Anleitung

SpoonDraft erzeugt Schnitzschablonen für Holzlöffel: Draufsicht, Seitenprofil und 3D-Vorschau, gespeichert als PDF, SVG oder Laser-SVG in Originalgröße. Diese Anleitung hat zwei Teile: [Erste Schritte](#erste-schritte) führt in fünf Schritten von der Löffelart bis zum Ausdruck, die [Referenz](#referenz) beschreibt jede Funktion einzeln.

[English version: GUIDE.md](GUIDE.md)

Die Bilder zeigen die deutsche Oberfläche. Die Sprache stellst du oben rechts ein, siehe [Sprache](#sprache).

## Erste Schritte

### 1. Löffelart wählen

Oben links wählst du, was du schnitzen willst: Esslöffel, Kochlöffel, Kaffeelöffel oder Schöpfkelle. Jede Art bringt eigene Startwerte mit. Das Blatt in der Mitte und die 3D-Ansicht zeigen sofort den Löffel dazu.

![Übersicht: Löffelart, Maße, Vorschau, 3D-Ansicht und Speichern](anleitung/de-uebersicht.png)

### 2. Maße anpassen

Unter der Löffelart liegen die Maße in fünf Gruppen: Gesamt, Laffe, Stiel, Seitenprofil und Erweitert. Klicke eine Gruppe an, um sie aufzuklappen, und ziehe die Regler. Jede Änderung siehst du sofort auf dem Blatt. Die Laffenform und das Griffende wählst du aus einem Katalog (Knopf „Formen“).

![Gruppe Laffe mit Reglern und Laffenform](anleitung/de-masse.png)

Als Anhaltspunkte stehen bei den Reglern Richtwerte: Crank-Winkel Kochlöffel 0–15°, Esslöffel 15–20°, Servierlöffel bis 30°, Kellen 60–90°; Knickposition bei Löffeln 25–33 % der Laffenlänge, bei Kellen nahe am Hals. Ein Esslöffel hat meist einen Laffenanteil von etwa einem Drittel der Gesamtlänge; die Angaben rechts zeigen deinen Wert.

### 3. Vorschau und 3D lesen

Das Blatt zeigt die Schablone in Originalgröße. Links steht das Seitenprofil mit der echten Biegung, rechts die Draufsicht als abgewickelter Umriss. Die waagrechte Knicklinie verbindet beide Ansichten; im Stiel stehen sie auf gleicher Höhe. Unten im Schriftfeld stehen die wichtigsten Maße, der Rohling und die Formkennungen.

Mit dem Mausrad zoomst du in die Vorschau, durch Ziehen verschiebst du sie, „Ganzes Blatt“ oder ein Doppelklick zeigt wieder alles. Das kleine 3D-Fenster zeigt den Löffel als Körper: Zum Drehen ziehen. Die drei Knöpfe oben im Fenster wechseln die Darstellung (Holz, Technisch, Drahtgitter), tauschen die Plätze von Zeichnung und 3D und blenden 3D aus.

![Zoom mit Übersicht und 3D-Ansicht](anleitung/de-vorschau3d.png)

### 4. Als PDF, SVG oder Laser-SVG speichern

Rechts oben speicherst du die Schablone:

- **PDF speichern**: zum Drucken. Die Datei hat Originalgröße.
- **SVG speichern**: zum Weiterbearbeiten in einem Zeichenprogramm.
- **Laser-SVG**: für Laserschneider. Rot wird geschnitten, Blau graviert.

Die Dateien heißen zum Beispiel `spoondraft-essloeffel-170mm.pdf`. Der PDF-Export lädt eine Bibliothek aus dem Internet; ohne Verbindung speicherst du als SVG.

![Speichern-Knöpfe, Angaben und Warnung](anleitung/de-speichern.png)

### 5. In Originalgröße drucken

1. Öffne die PDF-Datei und wähle im Druckdialog „Tatsächliche Größe“ oder 100 %. „An Seite anpassen“ verändert die Maße.
2. Miss nach dem Druck den 50-mm-Balken oben links nach. Stimmt er, stimmt die ganze Schablone.
3. Passt die Schablone nicht auf ein A4-Blatt, wählst du bei „Papier bei langen Schablonen“ A3 oder 2 × A4. Bei 2 × A4 druckst du beide Seiten, überlappst sie und legst die zweite Seite an der Linie „Kante von Seite 2 hier anlegen“ an.
4. Die Faser des Rohlings soll entlang des Stiels laufen. Schneide zuerst das Seitenprofil aus: Es ist der Ausgangspunkt, die Draufsicht folgt danach.

![50-mm-Balken, Drucktipps und Papierwahl](anleitung/de-drucken.png)

## Referenz

Jede Funktion hat einen eigenen Abschnitt. Das **Grundset** ist immer an. **Zusatzfunktionen** schaltest du im Dialog ⚙ („Standardwerte“, unten bei „Zusatzfunktionen“) einzeln ab; sie sind standardmäßig an.

### Grundset

<a id="loeffelart"></a>
#### Löffelart

**Grundset.** Vier Knöpfe oben im Bedienfeld: Esslöffel, Kochlöffel, Kaffeelöffel, Schöpfkelle. Ein Klick setzt alle Maße auf die Startwerte der Art (die Werkseinstellung oder deine [Standardwerte](#standardwerte)). Bisherige Änderungen gehen dabei verloren; sichere einen Entwurf vorher unter [Meine Löffel](#meine-loeffel).

<a id="bedienfeld"></a>
#### Bedienfeld

**Grundset.** Hier stellst du alle Maße ein, in fünf Gruppen:

| Gruppe | Inhalt |
|---|---|
| Gesamt | Gesamtlänge (100–350 mm), Papier bei langen Schablonen |
| Laffe | Länge, Breite, Tiefe, breiteste Stelle, Laffenform, Händigkeit |
| Stiel | Halsbreite, größte Griffbreite, Griffende, Facettenlinien am Hals |
| Seitenprofil | Stielstärke am Hals, Crank-Winkel, Knickposition |
| Erweitert | Stielstärke am Griffende, Verdickung am Hals, Lage der größten Griffbreite, Übergang am Knick, Stielkrümmung, Wandstärke, Mindestwandstärke |

Die Gruppen klappen auf und zu. Laffenform und Griffende wählst du aus einer Galerie mit Vorschaubildern; die Kennungen (z. B. L01, G01) stehen im Schriftfeld der Schablone. Händigkeit spiegelt asymmetrische Laffenformen.

![Gruppe Laffe mit Reglern und Laffenform](anleitung/de-masse.png)

<a id="formen"></a>
#### Formen

**Grundset.** Der Formenkatalog: Laffen und Griffenden, jeweils mit Kennung (Laffen L…, Griffenden G…). Dazu kommen die Formvorgaben Ei (LE), Feige (LF), Squoval (LS) und Oval (LO). Öffne die Galerie mit dem Knopf „Formen“ und klicke eine Form an. Eigene Formen aus dem [Formeditor](#editor) oder aus einem Bild ([Eigene Formen](#eigene-formen)) stehen in derselben Galerie.

![Galerie der Laffenformen](anleitung/de-formen.png)

<a id="geometrie"></a>
#### Geometrie

**Grundset.** Rechnet aus den Maßen die Schablone: Draufsicht mit abgewickeltem Umriss, Seitenprofil mit der echten Biegung, Facettenlinien, Knicklinie, Mittellinien und Schriftfeld. Alle Maße sind in Millimetern. Das Blatt ist A4, wenn die Schablone darauf passt; sonst gilt deine Wahl A3 oder 2 × A4 (Regler „Papier bei langen Schablonen“). Passt die Schablone auch nicht auf 2 × A4, nimmt SpoonDraft A3 und vermerkt „zu breit für A4“.

Crank-Winkel und Knickposition hängen zusammen: Liegt der Knick weit hinten, ist nur ein begrenzter Crank möglich, sonst klappt die Laffenspitze über. Die Angaben warnen dann.

<a id="vorschau"></a>
#### Vorschau

**Grundset.** Das Blatt in der Mitte zeigt die Schablone so, wie sie gedruckt wird. Es zeichnet sich bei jeder Änderung neu. Zusätzlich zeigt der Bildschirm Hilfslinien, die nicht in PDF und SVG landen (z. B. die der [Wandstärke](#wandstaerke)).

<a id="zoom"></a>
#### Zoom

**Grundset.** Mausrad: zoomen. Ziehen: verschieben. Doppelklick oder „Ganzes Blatt“: zurück zur Gesamtansicht. Eine Mini-Übersicht zeigt, welchen Ausschnitt du siehst.

![Zoom mit Mini-Übersicht](anleitung/de-vorschau3d.png)

<a id="ansicht3d"></a>
#### 3D-Ansicht

**Grundset.** Der Löffel als Körper im kleinen Fenster oben rechts im Blatt. Ziehen dreht ihn. Drei Knöpfe im Kopf des Fensters:

- Darstellung wechseln: Holz, Technisch (grau mit Linien an Umriss, Laffenrand, Facetten und Kiel), Drahtgitter.
- Ansichten tauschen: 3D groß, Zeichnung klein, und zurück.
- Ausblenden: blendet 3D aus (Augensymbol).

Deine Wahl bleibt im Browser gespeichert. Die 3D-Ansicht lädt eine Bibliothek aus dem Internet.

<a id="angaben"></a>
#### Angaben und Warnungen

**Grundset.** Rechts neben dem Blatt stehen die Angaben: Rohling (kleinstes Holzstück, in dem der Löffel Platz hat), Drop, Blattgröße und Laffenanteil mit Richtwert. Darunter erscheinen Warnungen:

- Crank über 15° (Grenze einstellbar): Im geradfaserigen Holz entsteht Kurzfaser an Hals und Laffenspitze. Nimm einen gebogenen Ast.
- Crank größer als bei der Knickposition möglich.
- Esslöffel-Laffe größer als 45 × 65 mm oder tiefer als 8 mm (Grenzen einstellbar): zu groß für den Mund bzw. schwer leer zu essen.

Unter „Drucktipps“ stehen die Hinweise zum [Drucken](#5-in-originalgröße-drucken).

![Angaben und Warnung](anleitung/de-speichern.png)

<a id="export"></a>
#### Speichern: PDF, SVG, Laser-SVG

**Grundset.** Drei Knöpfe rechts oben:

| Knopf | Datei | Inhalt |
|---|---|---|
| PDF speichern | `spoondraft-<Löffelart>-<Länge>mm.pdf` | Schablone in Originalgröße auf A4, A3 oder zwei A4-Seiten |
| SVG speichern | `….svg` | dieselbe Zeichnung als Vektordatei |
| Laser-SVG | `…-laser.svg` | ein Stück in Originalgröße in mm mit 5 mm Rand, nur Linien |

Das Laser-SVG enthält alle Linien der Schablone, also Draufsicht und Seitenprofil, in zwei Farben. Rot (0,01 mm) wird geschnitten: der Umriss. Blau (0,1 mm, durchgehend) wird graviert: Mittellinie, Knicklinie, Facetten, Bezugslinien und Strichlinien. Laser-Programme wie LightBurn oder xTool ordnen die Farben Ebenen zu. Nicht enthalten sind Texte, Schraffur, Füllungen, 50-mm-Balken, Maßpfeil, Schriftfeld, Muldenlinien und die Anlegelinien von 2 × A4. Prüfe die Größe in deiner Laser-Software, bevor du schneidest.

Wo das Speichern nicht möglich ist (etwa in der eingebetteten Ansicht in claude.ai), gibt es stattdessen „SVG-Code kopieren“.

![Speichern-Knöpfe](anleitung/de-speichern.png)

<a id="sprache"></a>
#### Sprache

**Grundset.** Die Auswahl oben rechts stellt die Oberfläche auf Deutsch, Niederländisch, Englisch, Französisch, Schwedisch, Spanisch, Italienisch, Norwegisch, Dänisch oder Polnisch um. Das Schriftfeld der Schablone folgt der Sprache; bei Polnisch ist es englisch. Die Wahl bleibt im Browser gespeichert.

![Kopfzeile mit Sprache, Design, Meine Löffel, Standardwerten und Rundgang](anleitung/de-kopfzeile.png)

<a id="design"></a>
#### Design

**Grundset.** Das Menü „Design“ bietet vier Designs (Salbei, Ahorn, Papier & Terrakotta, Morgenhimmel) und die dunkle Darstellung. Beides ändert nur das Aussehen der Seite, nicht die Schablone.

![Design-Menü](anleitung/de-design.png)

<a id="standardwerte"></a>
#### Standardwerte

**Grundset.** Der Knopf ⚙ öffnet den Dialog „Standardwerte“:

- **Für alle Löffelarten**: Felder, die in der Werkseinstellung für alle Arten gleich sind, hier mit einem Wert für alle.
- **Startwerte je Löffelart**: eigene Startwerte für die übrigen Felder. Sie gelten ab dem nächsten Klick auf eine Löffelart.
- **Richtwerte und Warngrenzen**: Laffenanteil, Crank-Warnung, Grenzen für die Esslöffel-Laffe.
- **Zusatzfunktionen**: ein Schalter je Zusatzfunktion, siehe unten.

Geänderte Werte sind markiert, ↺ setzt ein Feld zurück, „Auf Werkseinstellung“ setzt alles zurück. „Übernehmen“ speichert im Browser. Die Schalter der Zusatzfunktionen wirken sofort und liegen im Grundset, damit du eine abgeschaltete Funktion immer wieder anschalten kannst.

![Dialog Standardwerte](anleitung/de-standardwerte.png)

### Zusatzfunktionen

Abgeschaltete Zusatzfunktionen verschwinden aus der Oberfläche, ihre Werte bleiben erhalten, und die Schablone ändert sich nicht.

![Schalter für die Zusatzfunktionen](anleitung/de-zusatz.png)

<a id="hinweise"></a>
#### Hinweis Faser und Kröpfung

**Zusatzfunktion.** Ein aufklappbarer Hinweis als erste Zeile der Gruppe „Seitenprofil“. Er sagt: Zuerst das Seitenprofil aussägen, die Faser entlang des Stiels laufen lassen, bei geradem Holz nur wenig Kröpfung, für mehr einen Krummast wählen, dessen Wuchs dem Profil folgt.

![Hinweis in der Gruppe Seitenprofil](anleitung/de-seitenprofil.png)

<a id="eigene-formen"></a>
#### Eigene Formen

**Zusatzfunktion.** Laffe oder Griffende aus einem Bild hochladen: unter der Galerie „Eigene Form hochladen“. Geeignet ist eine SVG- oder Bilddatei mit einer dunklen Umrisslinie oder gefüllten Form auf hellem oder durchsichtigem Grund. Bei der Laffe zeigt die Spitze nach oben, der Hals nach unten; beim Griffende liegt der Ansatz am Stiel unten. Die Größe ist egal, nur die Proportionen zählen. Eigene Formen lassen sich entfernen und als Datei (`.json`) speichern, teilen und wieder laden.

![Galerie mit „Eigene Form hochladen“](anleitung/de-formen.png)

<a id="zufall"></a>
#### Zufallsdesign

**Zusatzfunktion.** Der Knopf „Zufallsdesign“ neben der Löffelart würfelt Laffenform, Griffende und Maße in sinnvollen Grenzen um die Startwerte der gewählten Löffelart. Papier, Facettenlinien und Löffelart bleiben, eigene Formen werden nicht gewählt. Der Knopf ändert deine Maße; sichere Entwürfe, die du behalten willst, vorher unter [Meine Löffel](#meine-loeffel).

<a id="editor"></a>
#### Formeditor

**Zusatzfunktion.** „Form bearbeiten“ neben Laffenform und Griffende öffnet den Editor. Du ziehst Kontrollpunkte; eine Kurve verbindet sie. Ein Doppelklick auf die Linie fügt einen Punkt hinzu, ein Doppelklick auf einen Punkt (oder Entf) entfernt ihn, Strg+Z macht rückgängig. Je Hälfte sind 4 bis 16 Punkte möglich. „Symmetrisch“ und „Asymmetrisch“ legen fest, ob beide Hälften gleich sind. Eine Live-Draufsicht zeigt den ganzen Löffel, Warnungen weisen auf Überhang, Engstellen und ungewöhnliche Proportionen hin. „Bild zum Nachzeichnen“ legt ein Bild hinter die Zeichenfläche. „Übernehmen“ speichert die Form als eigene Form, „Als SVG speichern“ exportiert sie.

![Formeditor](anleitung/de-editor.png)

<a id="meine-loeffel"></a>
#### Meine Löffel

**Zusatzfunktion.** Der Knopf „Meine Löffel“ öffnet eine Liste mit deinen Entwürfen. „Aktuellen Stand speichern“ legt einen Eintrag mit Maßen, Name, Notiz und bis zu drei Fotos des fertigen Löffels an. Mit „Laden“ holst du einen Entwurf zurück, mit „Bearbeiten“ änderst du Name, Notiz und Fotos, mit „Löschen“ entfernst du ihn. Die Einträge liegen nur in diesem Browser; Fotos landen nie auf der Schablone. „Sicherung speichern“ und „Sicherung laden“ schützen vor Datenverlust, „Als Datei teilen“ gibt einen einzelnen Entwurf weiter.

![Liste mit einem gespeicherten Entwurf](anleitung/de-meine-loeffel.png)

<a id="wandstaerke"></a>
#### Wandstärke-Hilfslinien

**Zusatzfunktion.** Mit dem Regler „Mindestwandstärke“ (Gruppe Erweitert) zeichnet die Vorschau gestrichelte blaue Hilfslinien: in der Draufsicht um das Maß nach innen versetzt vom Laffenrand, im Seitenprofil unter der Mulde. Eine Tiefenmarke am tiefsten Punkt zeigt die Muldentiefe und den Restboden. Ist der Boden dünner als die Mindestwandstärke, wird die Marke rot und eine Warnung erscheint: Nur bis zur gestrichelten Linie aushöhlen. Die Hilfslinien erscheinen nur am Bildschirm, nicht in PDF und SVG.

![Gestrichelte Hilfslinie und Tiefenmarke](anleitung/de-wandstaerke.png)

<a id="rundgang"></a>
#### Rundgang

**Zusatzfunktion.** Beim ersten Besuch bietet SpoonDraft einen kurzen Rundgang an. Er hebt nacheinander Löffelart, Maße, Vorschau, 3D-Ansicht, Speichern-Knöpfe und ⚙ hervor und erklärt sie in einer Sprechblase; der letzte Schritt zeigt den Knopf „?“ und verlinkt diese Anleitung. „Weiter“ und „Zurück“ blättern, Esc beendet. Du kannst die Seite währenddessen weiter bedienen. Über den Knopf „?“ neben dem Namen startest du den Rundgang jederzeit neu.

![Rundgang: Sprechblase an den Maßen](anleitung/de-rundgang.png)
