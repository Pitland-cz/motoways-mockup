# Motoways App v2 — Clickable Mockup

Board-approved visual mockup for the Motoways motorcycle navigation app (Czech UI, dark mode).

## Live preview

GitHub Pages: https://pitland-cz.github.io/motoways-mockup/

Open `index.html` for the flow overview, or click any screen card to jump into the prototype.

## Screens

| # | Screen | File |
|---|---|---|
| — | Flow overview | `index.html` |
| 1 | HOME / Menu | `01-home.html` |
| 2 | MAP / Navigation | `02-map.html` |
| 3 | PLANNER (V2 with AI toggle) | `03-planner.html` |
| 4 | IN-RIDE HUD | `04-hud.html` |
| 5 | FLOW SUMMARY | `05-flow-summary.html` |

## Navigation wiring

- **Overview** → click any screen card to open that screen.
- **Home** → "KAM DNES" opens Map; "Plánovač" opens Planner; "Historie" / last-ride card opens Flow Summary.
- **Map** → "Spustit navigaci" opens HUD.
- **Planner** → back arrow returns to Home; "SPUSTIT JÍZDU" opens HUD.
- **HUD** → "■ Ukončit" opens Flow Summary; "⏸ Pauza" returns to Home.
- **Flow Summary** → "Naplánovat další" opens Planner.

Every screen has a `← Přehled` pill (back to overview) and a `🏠 Domů` pill in the corner.

Source approvals: WAY-336 (brand assets), WAY-841 (board feedback), WAY-842 (final mockup approval).
