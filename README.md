# Biber-Blockwelt

Ein kleines Lernspiel zur Vorbereitung auf den [Informatik-Biber](https://bwinf.de/biber/), abgestimmt auf **Klassenstufe 5–6** (12 Aufgaben in 35 Minuten, je 4 leicht / mittel / schwer).

**Spielen:** https://mackartor-dev.github.io/informatik-biber-informatik-f-r-alle/

## Was drin ist

- **15 Aufgaben als Mini-Spiele** in einer Block-Welt, sortiert nach vier Themen-Welten:
  - Wiese – Befehle und Programme (Reihenfolge, Schleife, eingeschränkter Befehlssatz)
  - Höhle – Codes und Geheimnisse (Binärzahlen, Lauflängen-Kodierung, XOR-Verschlüsselung, Paritäts-Fehler)
  - Wald – Sortieren und Entscheiden (Sortieren mit zwei Regeln, Entscheidungsbaum, Sortier-Netzwerk, Optimierung)
  - Berge – Logik und Wege (Breitensuche, Logik-Gatter, Graph-Färbung, kürzester Weg)
- **Vorlesen für alles:** Aufgaben, Antwortkarten, Tipps und Erklärungen. Der gerade gesprochene Satz und das Wort werden farbig markiert. Ein Tipp auf einen einzelnen Satz liest nur diesen Satz vor.
- **Legasthenie-freundlich:** gut lesbare Schrift (Lexend), große Zeilenabstände, kurze Sätze, einstellbare Schriftgröße und Lesetempo.
- **Probe-Biber:** 12 zufällig gewählte Aufgaben (4 / 4 / 4) mit 35-Minuten-Uhr, Auswertung erst am Ende.
- Nach jeder gelösten Aufgabe: „Profi-Wissen“, das erklärt, welches Informatik-Thema dahintersteckt.

## Technik

- Eine einzige Datei: `index.html` (HTML, CSS und JavaScript, keine Build-Schritte).
- Vorlesen nutzt die eingebaute Sprachausgabe des Browsers (Web Speech API). Welche deutschen Stimmen verfügbar sind, hängt vom Gerät ab. Am besten funktioniert es in Chrome, Edge und Safari.
- Alle Grafiken werden im Browser selbst erzeugt; nur die Schriften kommen von Google Fonts.
- Der Fortschritt (Kristalle, Einstellungen) wird nur lokal im Browser gespeichert (`localStorage`).

## Hinweis

Alle Aufgaben sind neu geschrieben und lehnen sich an die Themen des Informatik-Biber an. Dies ist kein offizielles Angebot der Bundesweiten Informatikwettbewerbe (BWINF). Original-Aufgaben vergangener Jahre gibt es unter [bwinf.de/informatik-biber/aufgaben](https://bwinf.de/informatik-biber/aufgaben/), den Schnupper-Biber unter [wettbewerb.informatik-biber.de](https://wettbewerb.informatik-biber.de/).

Lizenz: GPL-3.0 (siehe `LICENSE`).
