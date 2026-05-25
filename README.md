# Motoways App v2 — Clickable Mockup

Board-approved visual mockup for the Motoways motorcycle navigation app (Czech UI, dark mode).

## Live preview

GitHub Pages: https://pitland-cz.github.io/motoways-mockup/

Opens directly into the **Home phone mockup** — click `KAM DNES` → Map, `Plánovač` → Planner, the last-ride card → Flow Summary, etc.

## Screens

| # | Screen | File |
|---|---|---|
| 1 | HOME / Menu (landing) | `index.html` / `01-home.html` |
| 2 | MAP / Navigation | `02-map.html` |
| 3 | PLANNER (V2 with AI toggle) | `03-planner.html` |
| 4 | IN-RIDE HUD | `04-hud.html` |
| 5 | FLOW SUMMARY | `05-flow-summary.html` |
| — | Screen map (secondary) | `flow.html` |

## Navigation wiring

- **Home (landing)** → `KAM DNES` opens Map · `Plánovač` opens Planner · `Historie` / last-ride card opens Flow Summary. A discreet `Mapa obrazovek →` link in the corner opens the secondary screen-map (`flow.html`).
- **Map** → `Spustit navigaci` opens HUD.
- **Planner** → back arrow returns to Home · `SPUSTIT JÍZDU` opens HUD.
- **HUD** → `■ Ukončit` opens Flow Summary · `⏸ Pauza` returns to Home.
- **Flow Summary** → `Naplánovat další` opens Planner.

Every non-home screen has a `🏠 Domů` pill in the corner.

Source approvals: WAY-336 (brand assets), WAY-841 (board feedback), WAY-842 (final mockup approval).
