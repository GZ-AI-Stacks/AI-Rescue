# AI.-Ready Rescue — Repo

Live-URL (Ziel): https://www.gz-ai-stacks.de/ai-rescue/ oder eigene Subdomain.

## Struktur

```
ai-rescue-repo/
├── index.html          # Landingpage (Verkaufsseite)
├── HANDBUCH.html        # Vollständiges Handbuch
├── agb.html             # AGB
├── widerruf.html        # Widerrufsbelehrung + Muster-Formular
├── impressum.html        # Impressum (§ 5 DDG)
└── Dokumente/            # Datenschutz, EULA, Technisches Datenblatt
```

## Stand 2026-08-08 (durch Claude vorbereitet)

- [x] Landingpage `index.html` mit Cyberpunk-Look (passend zur App)
- [x] AGB, Widerruf, Impressum, Datenschutz erstellt
- [x] Preis: 24,90 € Einmalkauf (validiert per Wettbewerbsrecherche)
- [x] Kauf-Button `aria-disabled="true"` mit „DEMNÄCHST"-Tag — **Digistore-Checkout-URL später einsetzen**
- [x] Update-Garantie: 3 Jahre
- [x] HANDBUCH.html im App-Look erstellt

## TODOs für Gee

1. **Digistore-Produkt anlegen** — Angaben liegen fertig in
   `W:\04_Uebersicht-Digistore\14-AI-Rescue\Digistore-Anlage-Angaben.txt`.
   Danach Checkout-URL in `index.html` einsetzen (Grep nach `aria-disabled="true"`).
2. **Produktbild** erstellen und im Digistore24-Formular hochladen.
3. **Bestellformular** im Digistore24-Konto selbst anpassen (nicht Standard stehen lassen).
4. **DPMA-/TMview-Markencheck** für "AI.-Ready Rescue" direkt im Register durchführen.
5. **Repo auf GitHub erstellen**: `GZ-AI-Stacks/AI-Rescue` (analog RootGuide) und Pages aktivieren.
6. **Karte in Homepage-v2** `produkte.json` ergänzen, sobald das Repo live ist.

## Verbotene Begriffe (Digistore-Compliance!)

In Verkaufstexten NIE: „für immer", „lebenslang", „dauerhaft", „unbegrenzt", „lifetime".
Stattdessen: „jederzeit nutzen", „24/7-Zugang", „Einmalkauf — Updates 3 Jahre inklusive".

Vor Digistore-Antrag: `grep -i "lebenslang\|für immer\|dauerhaft\|unbegrenzt\|lifetime"` über alle HTMLs.

## Quellen

- App-Quelle (nicht in diesem Repo — siehe `.gitignore`): `AIRescue.cs`, kompiliert zu
  `AI.-Ready Rescue.exe`, beides bleibt lokal/im Digistore-Auslieferungspaket.
- Freischaltcodes (nicht in diesem Repo): siehe `projekt_ai_rescue.md`-Memory.
