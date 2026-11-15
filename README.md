# BTL – Beat the Leis · Beat Carla

Comic-Timing-Boxspiel im C64-Stil. Läuft im Browser auf PC, Tablet und Handy – als Web-App auch offline und im Vollbild-Querformat.

**Spielen:** https://katzenkotz-droid.github.io/BTL-Game/

## So geht's
- **Schlagen:** Leertaste / Klick / Tippen, wenn der Marker in der goldenen Mitte ist (Volltreffer). Grün = schwacher Treffer, dazwischen = Block und kostet Kondition.
- **60 Sekunden** pro Level, Kondition erholt sich im Kampf nicht.
- **Minispiele** vor jedem Level bringen Boni (Superschlag `S`, Extra-Kondition `K`), max. 5 im Inventar, 1 pro Kampf.
- **Gegner:** Leis (Boxring) oder Carla (Küche), je 5 Level + Ultra-Modus.
- **Esc / Strg+C** = Kampf abbrechen · **M** = Ton · **P** = Pause

## Auf dem Android-Handy installieren
1. Den Link oben in **Chrome** öffnen.
2. Menü **⋮** → **„App installieren“** bzw. **„Zum Startbildschirm hinzufügen“**.
3. Ab jetzt startet BTL vom Startbildschirm im Vollbild-Querformat, auch ohne Internet.

## Dateien
| Datei | Zweck |
| --- | --- |
| `index.html` | das komplette Spiel (Grafik, Sound, Logik) |
| `manifest.webmanifest` | App-Name, Icon, Querformat, Vollbild |
| `sw.js` | Offline-Speicher (Service Worker) |
| `icons/` | App-Icons |

**Update veröffentlichen:** neue `index.html` hochladen und in `sw.js` die Versionsnummer (`btl-v2.4`) erhöhen.
