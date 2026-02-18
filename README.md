# CBB Stats Prototype

This repository now includes a **clickable, visual prototype** so you can see what a final product could look like before investing in deeper code reading.

## What this prototype shows

- A dashboard layout for college basketball stats
- KPI cards (pace, offensive efficiency, defensive efficiency, net rating)
- Team selector + date range controls
- Example trend chart area
- Recent game table
- "Player Impact" mock section

> Note: this is a static prototype (no backend data yet).

## How to view it locally

From the repo root:

```bash
python3 -m http.server 4173
```

Then open:

- `http://localhost:4173/prototype/`

## Next step if you like this direction

If this layout is close to what you want, I can implement it as a real app shell with:

1. API/data integration points
2. Real charts and sorting/filtering
3. Team/game drill-down pages
