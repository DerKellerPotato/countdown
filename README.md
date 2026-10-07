# Countdown

Präsentations-Timer im isometrischen SimCity-Look: Ein Zug fährt vom Hauptbahnhof durch Vorstadt, Felder, Wald, Industrie, einen Bergtunnel und über den Fluss bis zum Ziel. Wenn er ankommt, ist die Zeit um.

**Live:** https://derkellerpotato.github.io/countdown/?min=5

## Bedienung

| Aktion | Wirkung |
|---|---|
| Klick | Start (schaltet in den Vollbildmodus) / Pause |
| Leertaste | Start / Pause |
| R | Neustart |
| Z | Ansicht wechseln: Zug → Balken → Zahlen |
| F | Vollbild |

## Link-Optionen

Mit `&` kombinierbar, z. B. `?min=10&ansicht=zahlen`.

| Parameter | Bedeutung | Beispiel |
|---|---|---|
| `min`, `sek` | Dauer | `min=5`, `sek=90` |
| `ansicht` | `zug` (Standard), `balken`, `zahlen` | `ansicht=balken` |
| `bg`, `farbe`, `zug` | Farben (Hex ohne #) für Hintergrund, Schrift, Balken | `bg=084F6A` |
| `uhr=klein` | große Uhr oben rechts ausblenden | |
| `strecke=0` | Streckenbalken unten ausblenden | |
| `hinweis=0` | Bedienhinweis ausblenden | |
| `auto=1` | sofort starten (Vollbild braucht trotzdem einen Klick oder F11) | |

Schrift: Century Gothic Bold (falls installiert).
