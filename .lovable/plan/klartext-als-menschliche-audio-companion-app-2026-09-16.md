# KLARTeXt. als menschliche Audio-Companion-App

## Zielbild
KLARTeXt. wird eine **mobile-first Digital Companion App** und eine **interaktive Audio-Begleitung** zur gedruckten Ausgabe. Sie soll ruhig, persönlich und bewusst gestaltet wirken – nicht wie ein generisches KI-Wellness-Produkt.

Ausdrücklich ausgeschlossen sind:
- die erdig-dunkle „Luxury Interior“-Pinterest-Collage aus der Negativreferenz
- austauschbare KI-Plakate, Wellness-Klischees, Gradient-Orbs und seelenlose Moodboard-Ästhetik
- Spotify-artiger Mini-Player
- redaktionelle Magazin-Website, News-Seite, Blog, Zeitungslayout, Artikel-Feed oder SaaS-Dashboard

## Festgelegte Designrichtung

### Farben
Eine eigenständige Mischung aus weichen Neutralen, klarer Farbe und einem tiefen Gegenton:
- **Cloud Dancer / gebrochenes Weiß:** `#F6F4E9` – ruhige Grundfläche
- **KLARTeXt.-Sand:** `#C1B094` – bewahrt den bestehenden Markenbezug
- **weiches Flieder:** `#DBD1ED` – unerwartete, moderne Farbfläche
- **gedämpftes Oliv:** `#8D8E1F` – sparsam für aktive Details
- **tiefes Weinrot:** `#3A0C0C` – Kontrast, Schrift und einzelne starke Flächen

Nicht jede Fläche verwendet alle Farben. Pro Bereich werden zwei ruhige Neutrale mit höchstens einem Farbton und einem dunklen Anker kombiniert.

### Schrift
Die bestehende Schriftkombination bleibt unverändert. Große, kurze Wörter oder Überschriften dürfen direkt auf klaren Farbblöcken stehen – wie in der zweiten Referenz, aber ruhiger, weniger werblich und passend zur Audio-App.

### Aufbau
Ein **Bento Companion** verbindet unterschiedlich große, funktionale Kacheln mit einzelnen ruhigen Vollflächen. Das ist kein Dashboard: Die Module dienen ausschließlich dem schnellen Einstieg in Audio, Begleitimpuls, Download und Ausgabe.

## Umsetzung

1. **App-Einstieg statt Magazinseite**
   - Kompakter, beim Scrollen erreichbarer Kopf mit Logo, Ausgaben und Magazin-Link.
   - Der Einstieg zeigt direkt die aktuelle Audio-Auszeit und wenige klare Schnellzugriffe.
   - Farbblöcke mit kurzen Überschriften strukturieren die Bereiche ohne lange redaktionelle Einleitung.
   - Eine reduzierte mobile Navigation führt zu den vorhandenen Hauptbereichen, ohne eine Spotify- oder Dashboard-Anmutung zu erzeugen.

2. **Großflächiger aktiver Hörmodus**
   - Beim Start eines Audios öffnet sich eine ruhige, große Hörfläche mit dem jeweiligen Bild als prägendem Hintergrund.
   - Titel, Fortschritt, Zeit und wenige große Bedienelemente liegen klar lesbar auf dieser Fläche.
   - Kein dauerhaft schwebender Mini-Player: Der Hörmodus bleibt der bewusste Fokus und lässt sich schließen, ohne den aktuellen Stand zu verlieren.
   - Es spielt immer nur ein Audio gleichzeitig; Tastaturbedienung, zugängliche Namen und Statusansagen bleiben erhalten.

3. **Karussell stabilisieren**
   - Kacheln, Statuspunkte und Bedienhinweis erhalten einen gemeinsamen zentrierten Rahmen im Audio-Farbband.
   - „Zum Wechseln seitlich wischen …“ sitzt fest unter den Kacheln und kann durch das Hintergrundbild nicht mehr nach rechts wandern.
   - Wischen, Pfeiltasten und ausreichend große Touch-Ziele bleiben erhalten.

4. **Audio und Begleittext sichtbar koppeln**
   - Der wechselnde Text grenzt direkt an das zugehörige Audio-Modul an.
   - Ein wiederkehrender Farbblock oder schmaler Farbcode verbindet aktive Kachel und Begleittext eindeutig.
   - Downloads und Quellenangaben bleiben beim Begleittext; die Audiokachel selbst bleibt auf das Hören konzentriert.

5. **Glas sparsam und gezielt**
   - Die große Player-Kachel wird überwiegend opak und ruhig, mit präziser Lichtkante und weichem Schatten.
   - Liquid Glass erscheint nur dort, wo es funktional hilft: kleine Bedienelemente, Badge oder Menüfläche.
   - Bestehende dekorative Glows und übermäßige Transparenz werden reduziert.

6. **Menschliche, taktile Bildwelt**
   - Vier zusammengehörige Covermotive mit Papier, Keramik, Stoff, Schatten und ungewöhnlichen Ausschnitten in natürlichem Licht.
   - Keine Meditationsposen, Sonnenuntergänge, leuchtenden Landschaften, generischen Wohnraum-Collagen oder glatten KI-Wellness-Motive.
   - Die Motive wirken beobachtet und fotografisch komponiert, nicht künstlich perfekt.
   - Die Bildserie bleibt klein und gezielt, um Credits sparsam einzusetzen.

7. **Homescreen-App mit Anleitung**
   - Bestehendes Manifest, Standalone-Modus und Marken-Icons bleiben; kein Offline-Modus.
   - Im jederzeit erreichbaren Ausgaben-/Mehr-Menü steht „App auf Homescreen installieren“.
   - Android nutzt den verfügbaren Installationsdialog; auf iPhone erscheint „Teilen → Zum Home-Bildschirm“.
   - Ist die App bereits vom Homescreen geöffnet, wird der Hinweis ausgeblendet.

## Barrierefreiheit und Prüfung
- Genau ein Hauptbereich, sichtbare Tastaturfokusse, inklusive deutsche Beschriftungen, mindestens 44-Pixel-Ziele, ausreichende Kontraste und reduzierte Bewegung.
- Prüfung auf 402 × 725 sowie Desktop: Scrollen, Karussell, aktiver Hörmodus, Audiowiedergabe, Begleittextwechsel, Downloads, Installationshinweis und Ausgaben-Menü.
- Beide Inhaltsseiten behalten ihre eigenen vollständigen Metadaten.

## Technische Details
- Änderungen betreffen die beiden Inhaltsseiten, die gemeinsame Audiokarte, den aktiven Hörmodus, Navigation, Design-Tokens und neue Coverbilder.
- Die bestehende Audio- und Karusselllogik wird weiterverwendet und für den großflächigen Hörmodus gebündelt.
- Keine Anmeldung, keine Datenbank und kein Offline-Modus.
