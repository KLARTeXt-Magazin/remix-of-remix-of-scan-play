# Redesign: Editorial Japandi Audio-Bereiche

## Ziel
Die beiden Ausgaben wirken wie eine sorgfältig gestaltete, moderne Magazin-App statt wie eine generische Wellness- oder KI-Oberfläche. Die bestehende Bento-Struktur, Sand-, Salbei- und Walnusstöne sowie alle Funktionen bleiben erhalten.

## Umsetzung

1. **Audio-Bereich neu ordnen**
   - Das Karussell erhält einen klaren, zentrierten Inhaltsrahmen innerhalb des Farbbands.
   - „Zum Wechseln seitlich wischen …“ sitzt fest unter den Audiokacheln und kann durch die Ausrichtung des Hintergrundbildes nicht mehr seitlich verrutschen.
   - Statuspunkte, Kacheln und Hinweis bilden auf Mobilgeräten eine zusammengehörige vertikale Einheit.

2. **Player „editorial klar“ statt starkem Liquid Glass**
   - Große Player-Kacheln werden überwiegend opak und hell, mit einer präzisen Lichtkante, ruhigem weichem Schatten und klarer Typografie.
   - Glas bleibt nur als feines Detail an Playerleiste, Badge oder Bedienelementen; dekorative Glows und übermäßige Transparenz entfallen.
   - Die kräftigere Zeitleiste, lesbaren Zeitangaben und barrierefreien Bedienelemente bleiben erhalten.

3. **Begleittext sichtbar mit dem aktiven Audio verbinden**
   - Der wechselnde Text wird direkt an das Audio-Farbband angebunden, statt wie eine unabhängige weiße Fläche zu wirken.
   - Jede aktive Audio-Kachel erhält zusammen mit ihrem Begleittext einen dezenten, wiederkehrenden Farbakzent aus der bestehenden Palette.
   - Download und Quellenangabe bleiben im Begleitbereich; die Audiokachel selbst bleibt reduziert.

4. **Taktil-editoriale Bildwelt**
   - Vier neue, zusammengehörige Covermotive: Papier, Keramik, Stoff, Schatten und ungewöhnliche Ausschnitte in natürlichem Licht.
   - Keine Personen in Meditationspose, Sonnenuntergänge, leuchtenden Landschaften oder glatten KI-Wellness-Motive.
   - Motive werden quadratisch, ruhig und kontrastreich genug für Text/Badges angelegt; vorhandene leere Platzhalter werden ersetzt.
   - Bildgenerierung bleibt bewusst klein und effizient: nur die tatsächlich benötigte Cover-Serie.

5. **Moodboard-nahe Gesamtwirkung**
   - Mehr klare Flächen, asymmetrische redaktionelle Details und bewusste Leerräume.
   - Sand, Khaki, Walnuss und gebrochenes Weiß führen; Mineralblau bleibt ausschließlich für Fokus und aktive Zustände.
   - Ausgabe 01 und 02 erhalten dieselbe visuelle Logik, ohne Navigation, Inhalte, Installation oder Audioverhalten zu verändern.

## Barrierefreiheit und Prüfung
- Kontrast, sichtbare Tastaturfokusse, 44-Pixel-Ziele, ARIA-Texte und reduzierte Bewegung bleiben bestehen.
- Prüfung auf 402 × 725 sowie Desktop: Karussellposition, Wischen, Tastaturwechsel, Player, Begleittextwechsel, Downloads und Ausgaben-Menü.
- Beide Seiten behalten ihre eigenen vollständigen Metadaten; abschließend werden Vorschau und aktueller Build-Status geprüft.

## Technische Details
- Änderungen beschränken sich auf die beiden Inhaltsseiten, die gemeinsame Audiokarte, Design-Tokens/Styles und neue Coverbilder.
- Die bestehende Karussell- und Audiologik wird nicht neu geschrieben, sondern nur strukturell stabilisiert und visuell überarbeitet.
- Kein Offline-Modus und keine zusätzlichen App-Funktionen.
