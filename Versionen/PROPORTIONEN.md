# Löffelproportionen – Abgleich Recherche ↔ Generator (Stand Version 15)

Quelle: Recherche-Bericht im Chat „Proportionen eines Löffels“ (27.10.2026). Abgleich mit den Startwerten (`PRESETS`) aus Version 15.

## Kernaussagen der Recherche
- **Drittel-Regel:** Esslöffel-Laffe ≈ ⅓ der Gesamtlänge (mehrere unabhängige Schnitzer; Metallbesteck gemessen 29–33 %). Kochlöffel ≈ ¼, Servierlöffel ≈ ⅓, Kelle ≤ ¼, Taschen-/Kinderlöffel bis ½.
- **Mundgröße Esslöffel:** Laffe max. ≈ 45 mm breit, ≈ 65 mm lang, max. 7–8 mm tief (sonst erreicht die Oberlippe den Boden nicht). B/L ≈ 0,65–0,75.
- **Kleine Löffel nicht linear verkleinern** – Laffe behält Mindestgröße (Generator macht das bereits: Laffenlänge bleibt bei Änderung der Gesamtlänge gleich).
- **Crank-Lage:** ¼–⅓ der Laffenlänge vom Hals (= unsere `kp` 30 % und Sägeschnittlinie). **Crank-Winkel** 27–32° nur aus einer Quelle mit anderer Messweise; Metallbesteck 5–25° → unsere 18° (Sehne ↔ Stielachse) plausibel. Kochlöffel kaum Crank, Kelle bis 90°.
- **Hals:** Draufsicht ≈ 0,25–0,35 × Laffenbreite; Seitenansicht beim Esslöffel ≥ 10 mm hoch (Generator rechnerisch ≈ 12 mm, passt).
- **Goldener Schnitt (38,2 %):** im üblichen Bereich, aber nicht besser begründet als ⅓ – nicht als Standard verwenden.
- **Normen:** ISO 8442 regelt keine Maße; „DIN-Maße“ sind Herstellerkonventionen.
- **Kelle:** Laffe Ø 65–100 mm, Tiefe ≈ 0,45–0,65 × Ø, Suppenkelle bis ≥ 400 mm lang.

## Vergleich mit den Startwerten (Version 15)
| | Generator | Recherche | Bewertung |
|---|---|---|---|
| Esslöffel Laffenanteil | 64/160 = 40 % | ≈ 33 % | zu laffenlastig |
| Esslöffel Laffe B × L | 46 × 64 mm | max. ≈ 45 × 65 | Breite knapp drüber |
| Esslöffel Tiefe | 9 mm | max. 7–8 mm | zu tief |
| Esslöffel Halsbreite | 10 mm (0,22 × B) | 12–16 mm | etwas schmal |
| Kochlöffel Laffenanteil | 85/280 = 30 % | ≈ 25 % | etwas groß |
| Kochlöffel Crank | 8° | ≈ 0° | vertretbar |
| Kaffeelöffel | 30 %, 40 × 28 mm | 29–32 %, 42–46 × 29–31 | passt |
| Kelle Laffenanteil | 95/280 = 34 % | ≤ 25 % | Laffe zu groß / Stiel zu kurz |
| Kelle Tiefe | 30 mm (0,35 × Ø) | 0,45–0,65 × Ø | zu flach |
| Griffbreite | 20–28 mm | „meist ≤ 19 mm“ (nur eine Quelle) | widerspricht Spoon-Club-Auswertung → so lassen |

## Vorgeschlagene Umsetzung (in Version 16 vom 27.10.2026 umgesetzt, dazu Knopf „Zufallsdesign“)
1. **Startwerte anpassen** (`PRESETS`):
   - Esslöffel: L 170, bl 58, bw 42, bd 7, nw 12 (Laffe 34 %)
   - Kochlöffel: bl 70, bw 50, ca 5 (Laffe 25 %)
   - Kelle: L 330 (Laffe 29 %), bd 40
2. **Laffenanteil anzeigen** in den Fakten unter der Vorschau („Laffe 34 % der Länge“ + Richtwert je Löffelart), alle 7 Sprachen.
3. **Warnhinweise** wie die 15°-Warnung: Esslöffel bw > 45 oder bl > 65 → „Mundgröße“; Esslöffel bd > 8 → „Oberlippe erreicht den Boden nicht“.
4. **Schalter Rechts-/Linkshänder** für die asymmetrischen Laffen (d11, d12, d14, d23, d34 = L14, L15, L17, L26, L37): Profil links/rechts tauschen.
- Bewusst weggelassen: Goldener Schnitt als Standard, eigener Regler „Laffenanteil“.
- Hinweis: Neue Startwerte ändern die Ausgabe der Standardlöffel – Vergleich mit v15 also nur für die übrigen Fälle zeichengenau erwartbar.

## Wichtigste Quellen
- Woodworkers Institute (Nalezyty): https://woodworkersinstitute.com/wooden-spoon-design/
- Australian Wood Review (Chesworth): https://www.woodreview.com.au/how-to/the-green-wood-spoon
- Jögge Sundqvist, Slöjd in Wood (Auszug): https://blog.lostartpress.com/wp-content/uploads/2024/12/Spoons-from-Slojd-in-Wood.pdf
- Carolina's Sloyd: https://slojd.nl/en/how-to-make-a-nice-wooden-eating-spoon/
- Robin Wood: https://www.robin-wood.co.uk/shop/perfect-cooking-spoons/
- Pinewood Forge: https://pinewoodforge.com/spoon-designing/
- ISO 8442-2 (Auszug): https://cdn.standards.iteh.ai/samples/23095/f4a265ef2fbc40c0b22126dbb31fe3f3/ISO-8442-2-1997.pdf
