# World Cup 2026 — Interactive Knockout Bracket

A single-file, interactive radial visualization and simulator for the 2026 FIFA World Cup knockout stage.

**Live:** https://diegoauad.github.io/world-cup-2026-bracket/

## Features
- Radial bracket of all 32 knockout qualifiers in their real positions, converging to the trophy.
- Real Round-of-32 results are pre-filled; the rest are yours to decide — click a flag to advance it.
- **Simulate** the remaining matches, weighted by World Football Elo ratings (eloratings.net).
- **Monte Carlo** tool: run N simulations and see how often each team wins the cup.
- Hover any undecided match for kickoff time (in your local timezone), venue, and Elo model odds.
- Live results are fetched from TheSportsDB with a built-in fallback snapshot.

Built as a dependency-free `index.html` — just open it (or serve it) in a browser.
