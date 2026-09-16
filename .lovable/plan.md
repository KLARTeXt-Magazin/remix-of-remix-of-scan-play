# KLARTeXt. als mobile Digital Companion App

## Zielbild
KLARTeXt. wird eine **mobile-first Digital Companion App** und eine **interaktive Audio-Begleitung** zur gedruckten Ausgabe. Die Gestaltung bleibt ruhig, taktil und hochwertig, fühlt sich aber klar wie eine persönliche, touchfreundliche App an.

Ausdrücklich ausgeschlossen sind: redaktionelle Magazin-Website, News-Seite, Blog, Zeitungslayout, klassisches Editorial Design, Artikel-Feed und SaaS-Dashboard.

## Umsetzung

1. **App-Struktur statt Magazinseite**
   - Inhalte werden als kurze, scrollbare App-Bereiche mit modularen Kacheln organisiert.
   - Ein kompakter App-Kopf bleibt beim Scrollen erreichbar und bietet schnellen Zugriff auf Ausgaben und Magazin.
   - Eine mobile untere Navigation führt direkt zu „Heute“, „Audios“, „Gespeichert“ und „Mehr“; auf Desktop wird sie zurückhaltend angepasst.
   - Bestehende Inhalte und Ausgaben bleiben erhalten, werden aber als persönlicher Content Companion statt als Artikelstrecke präsentiert.

2. **Audio als primäre Erfahrung**
   - Das Audio-Karussell erhält einen stabilen, zentrierten Bereich innerhalb seines Farbbands.
   - „Zum Wechseln seitlich wischen …“ sitzt direkt unter den Kacheln und kann nicht mehr an den rechten Rand wandern.
   - Die große Kachel wird **editorial klar im Sinne von hochwertiger Produktgestaltung**, nicht im Sinne einer Magazinseite: überwiegend opak, ruhig, präzise Lichtkante, weicher Schatten.
   - Liquid Glass bleibt sparsam auf kleinen Player- und Bedienelementen; dekorative Glows und übermäßige Transparenz entfallen.

3. **Persistenter Mini-Player**
   - Beim Scrollen bleibt das aktive Audio als kompakter Mini-Player über der unteren Navigation erreichbar.
   - Er zeigt Cover, Titel, Wiedergabestatus und Play/Pause; ein Antippen führt zurück zum vollständigen Player.
   - Es spielt immer nur ein Audio gleichzeitig. Tastaturbedienung, zugängliche Namen und Statusansagen bleiben erhalten.

4. **Begleittext und Audio zusammenführen**
   - Der wechselnde Text wird visuell und räumlich direkt mit der aktiven Audiokachel verbunden.
   - Ein wiederkehrender Farbakzent kennzeichnet eindeutig, welcher Text zu welchem Audio gehört.
   - Download und Quellenangabe bleiben im Begleitbereich; die Audiokachel selbst bleibt auf das Hören fokussiert.

5. **Modulare Schnellzugriffe und Merken**
   - Kleine, touchfreundliche Kacheln bieten schnellen Zugriff auf aktuelle Audios, Übungen, Downloads und die nächste Ausgabe.
   - Audios können lokal auf dem Gerät als Favorit gespeichert und unter „Gespeichert“ schnell wiedergefunden werden.
   - Keine Anmeldung und keine neue Datenbank; die Merkliste bleibt bewusst gerätebezogen.

6. **Taktil-moderne Bildwelt**
   - Vier neue, zusammengehörige Covermotive mit Papier, Keramik, Stoff, Schatten und ungewöhnlichen Ausschnitten in natürlichem Licht.
   - Keine Meditationsposen, Sonnenuntergänge, leuchtenden Landschaften oder glatten KI-Wellness-Motive.
   - Die Bilder werden quadratisch, ruhig und kontrastreich für kleine mobile Kacheln gestaltet; leere Platzhalter werden ersetzt.
   - Die Bildserie bleibt klein und gezielt, um Credits sparsam einzusetzen.

7. **Homescreen-App und verständliche Anleitung**
   - Bestehendes Manifest, Standalone-Modus und Marken-Icons bleiben die technische Grundlage; kein Offline-Modus.
   - Im jederzeit erreichbaren Ausgaben-/Mehr-Menü steht die Aktion „App auf Homescreen installieren“.
   - Android nutzt den verfügbaren Installationsdialog; auf iPhone erscheint die kurze Anleitung „Teilen → Zum Home-Bildschirm“.
   - Ist die App bereits vom Homescreen geöffnet, wird der Hinweis ausgeblendet.

## Visuelle Richtung
- Führend: Sand, Khaki, Salbei, Walnuss und gebrochenes Weiß.
- Mineralblau ausschließlich für Fokus, aktive Auswahl und feine Orientierung.
- Klare Flächen, kompakte Module, großzügige Ruhe und taktile Fotos statt dekorativer KI-Effekte.
- Bento-Prinzip als funktionale App-Übersicht, nicht als Artikelraster oder Dashboard.

## Barrierefreiheit und Prüfung
- Genau ein Hauptbereich, sichtbare Tastaturfokusse, verständliche deutsche Beschriftungen, mindestens 44-Pixel-Ziele, ausreichende Kontraste und reduzierte Bewegung.
- Prüfung auf 402 × 725 sowie Desktop: untere Navigation, Scrollen, Karussell, Mini-Player, Audiowiedergabe, Begleittextwechsel, Favoriten, Downloads, Installationshinweis und Ausgaben-Menü.
- Beide Inhaltsseiten behalten ihre eigenen vollständigen Metadaten.

## Technische Details
- Änderungen betreffen die beiden Inhaltsseiten, gemeinsame Audio-/Navigationskomponenten, Design-Tokens und neue Coverbilder.
- Der Audiozustand wird auf Seitenebene gebündelt, damit Vollansicht und Mini-Player synchron bleiben.
- Favoriten werden ohne Konto lokal im Browser gespeichert; Audio- und Karussellverhalten bleiben ansonsten erhalten.
