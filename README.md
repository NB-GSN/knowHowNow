# Know-how Now

**Der Papiercomputer zum Ausprobieren** – ein Lernsimulator für den Know-how-Computer (WDR-Papiercomputer) von Wolfgang Back und Ulrich Rohde (WDR Computerclub, 1983). Gedacht für den Informatikunterricht und für Lehrkräftefortbildungen.

**Direkt im Browser starten:** https://nb-gsn.github.io/knowHowNow/

## Funktionen

- **Programmblatt** wie auf Papier: nummerierte Zeilen, ein Stift als Befehlszähler, Sprungpfeile machen Schleifen sichtbar.
- **Register mit Streichhölzern** (8 Register, in Fünfergruppen gebündelt).
- **Erklärung zu jedem Schritt** in Alltagssprache, Schritt zurück, Tempo-Regler, Turbo.
- **„Ich bin der Computer“**: Lernende ziehen selbst Streichhölzer aus der Schachtel in die Register und setzen den Stift – mit Rückmeldung bei jedem Schritt.
- **Geführte Tour** in fünf Kapiteln: Worum geht es? · Rundgang · Das erste Programm · Ich bin der Computer · Selbst programmieren.
- **Hintergrund**: Geschichte, Befehlssatz, Ablaufprotokoll, Programmier-Muster, Berechenbarkeit, Vergleich mit dem Von-Neumann-Rechner, Hinweise für den Unterricht, Quellen.
- **8 Beispielprogramme** und **8 Aufgaben mit automatischer Prüfung**.
- **Druckvorlage** für den echten Papiercomputer (Unplugged-Einstieg).
- **Ansicht für PC, Tablet und Handy**.

## Junior-Modus für Klasse 5/6

Oben lässt sich zwischen **Junior** und **Profi** umschalten. Der Junior-Modus zeigt dasselbe Modell kindgerecht:

- **Kisten A–D mit bunten Murmeln** (in Fünferreihen) statt Registern mit Streichhölzern
- **Bildkarten** statt Kürzeln: ➕ lege · ➖ nimm · ↪️ springe · ❓ leer? · 🛑 stopp – Programme entstehen durch Ziehen der Karten aufs Blatt
- **Murmeln per Hand ziehen** (Finger oder Maus) – auch im Modus „Ich bin der Computer“
- **10 Rätsel mit Sternen** in drei Typen: bauen, vorhersagen, Fehler finden
- **Eigene Tour** („Hallo, Murmel-Computer!“ und „Ich bin der Computer“)
- **🔤 echte Befehle** blendet die Original-Befehle ein – als Brücke zum Profi-Modus

## Befehle

| Befehl | Bedeutung |
|---|---|
| `inc r` | ein Streichholz in Register r legen |
| `dec r` | ein Streichholz aus Register r nehmen |
| `jmp z` | zu Zeile z springen |
| `isz r` | ist Register r leer? Dann die nächste Zeile überspringen |
| `stp` | Programmende |

## Technik

Eine einzige Datei (`index.html`), keine Installation nötig. Läuft in jedem aktuellen Browser. Schriftarten werden – falls erreichbar – von Google Fonts geladen.
