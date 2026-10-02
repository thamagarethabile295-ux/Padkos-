# Padkos Road Trip Planner

Plan a South African road trip in one page: pick your town and one of 100+ destinations, and get the route with overnight stops, places to stay, sights along the way, and a full budget priced with official petrol and diesel prices.

**Live site:** `https://<your-username>.github.io/padkos/`

## Features
- Route over the national road network with daily driving limits and overnight stops
- Budget: fuel (inland/coastal prices), tolls, accommodation, food, activities, park fees, car rental, 10% contingency
- 100+ places across all nine provinces, searchable and filterable
- Share a trip as a link, print or save as PDF, add to your phone's home screen
- Choices are remembered in your browser

## Updating fuel prices each month
Edit `fuel.json` on GitHub (pencil icon) and change the numbers under `prices`, `effective`, `checked`, `forecast`, and add a line to `history`. Commit; the site updates within a minute or two.

## Files
| File | What it is |
|---|---|
| `index.html` | The whole app |
| `fuel.json` | Monthly fuel prices |
| `manifest.webmanifest`, `icon*` | Home-screen app icon |

Distances, tolls and prices are planning estimates. Confirm with operators before booking.
