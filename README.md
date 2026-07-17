# Energiefresser-Jäger · Circular Quest Luzern

GPS-basierte Prototypen für den interaktiven Stadtrundgang zu Energieeffizienz in der Gastronomie.

## Live-Versionen

Die Wurzel (`index.html`) zeigt eine Auswahlseite, von der aus man zu den einzelnen Varianten gelangt.

| Variante | URL | Stil |
|---|---|---|
| **Energiefresser-Jäger** | https://ddfeusi.github.io/energiefresser-jaeger/pokemon/ | Verspielt: Monster fangen & anfreunden, Chiptune-Musik, Monsterdex |
| **Energie-Detektei** | https://ddfeusi.github.io/energiefresser-jaeger/detektiv/ | Seriös: Fälle lösen, Beobachtungsfragen, Beweisfotos, Schlussbericht |
| **Actionbound** | – | Bald verfügbar (`actionbound/`) |

## Gemeinsame Basis

- Gleiche Altstadt-Route (Bahnhofplatz → KKL → Seebrücke → Schwanenplatz → Grendel → Rathausquai → Unter der Egg → Weinmarkt → Mühlenplatz)
- 8 Standorte, 6 Indizien unterwegs, identische Energie-Fakten
- Reine Web-Apps: eine HTML-Datei pro Variante, kein Backend, GPS via Browser
- Test-Modus in beiden Versionen (Button unten): Route ohne GPS simulieren

## Hinweise

- Beobachtungsfragen der Detektei-Variante sind **Platzhalter** – vor Launch vor Ort verifizieren
- Standort-Koordinaten in den Arrays `ROUTE_PATH`, `SPOTS`/`CASES`, `CLUES` justierbar

*Ein Projekt von Verein Future Perfect · Prototypen erstellt mit Claude*
