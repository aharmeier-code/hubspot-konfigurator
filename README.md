# HubSpot Lizenz-Konfigurator

Interaktiver Preiskonfigurator für alle HubSpot Hubs und RYZE Digital AEO — im RYZE Digital Design.

🔗 **Live:** [hubspot-konfigurator.vercel.app](https://hubspot-konfigurator.vercel.app)

## Features

- **7 Produkte:** Marketing Hub, Content Hub, AEO, Sales Hub, Revenue Hub, Service Hub, Data Hub
- **Echtzeitkalkulation** — monatliche Gesamtkosten inkl. Seats
- **4 Laufzeiten** — 12 Monate monatlich/jährlich, 24 Monate, 36 Monate (bis –15 % Rabatt)
- **EUR Listenpreise** nach HubSpot DACH-Preisliste
- **Per-Seat-Logik** — Marketing Hub Starter per Seat, Pro/Enterprise Flatrate
- **Zusammenfassungs-Panel** — alle gewählten Hubs auf einen Blick
- **RYZE Digital Design** — schwarz/orange (#e8541a), Pill-Buttons, Backdrop-Blur-Nav

## Stack

Standalone HTML/CSS/JS — kein Framework, kein Build-Step. Einzige Datei: `index.html`.

## Preise (EUR, Stand 2026)

| Hub | Starter | Professional | Enterprise |
|-----|---------|-------------|------------|
| Marketing Hub | €15/Seat | €792/Mo | €3.530/Mo |
| Content Hub | €23/Mo | €500/Mo | €1.500/Mo |
| Sales Hub | €20/Seat | €100/Seat | €150/Seat |
| Revenue Hub | €25/Seat | €75/Seat | €120/Seat |
| Service Hub | €20/Seat | €100/Seat | €130/Seat |
| Data Hub | €20/Mo | €720/Mo | €2.000/Mo |
| AEO (Basic/Plus/Max) | €46/Mo | €92/Mo | €184/Mo |

## Deployment

```bash
vercel --prod --scope aharmeier-6175s-projects
```
