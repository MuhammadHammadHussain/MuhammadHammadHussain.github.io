# Trip planner

A single-file trip cost and time planner. No build step, no dependencies.

- **Routes**: your travel database. Each route (train, bus, flight...) has local departure and arrival times, time zone difference, airport check-in time, normal and lowest prices, and weeks to book ahead. Cities have a country, filled in automatically for known cities, and routes are searchable by country.
- **Plan a trip**: build one journey. Pick the starting city, then click suggested next stops or type a city. Every stop can be changed later (city and mode) and the times and costs recalculate from your routes. A missing route can be added on the spot. The Suggestions panel lists every way through your routes (Cheapest, Fastest, Best balance) with the difference from your current plan.
- **Saved trips**: the trips you saved, compared side by side with normal and lowest totals, travel time, back-home date and a "book by" date. Use Edit in planner to change one.
- The starting routes are **placeholder data**: shown in italic with a dashed border until you edit them. "Load placeholder data" asks you to type REPLACE before it overwrites anything.
- Click a **Placeholder** tag on a route or trip to keep it as real data, keep and lock it, or clear it. A lock icon on each route and trip protects it from accidental edits.
- **Undo / Redo** buttons (or Ctrl+Z / Ctrl+Y) step through your changes in the current session.
- Data is saved in your browser. Use Export / Import to back it up or move it.

## Use on GitHub Pages
1. Put `index.html` in the root of a repository.
2. Settings → Pages → Deploy from a branch → `main` / root.
3. Open `https://<your-username>.github.io/<repo>/`.
