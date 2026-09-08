# Autumn — homepage

A single, static homepage for Autumn: AI-enabled digital marketing for independent inns, B&Bs and boutique hotels.

- `index.html` — the whole page: markup, styles and the small amount of JavaScript it needs. No framework, no build step.
- `img/` — photography and the door sequence. Every scene is generated (Higgsfield Soul Location / Soul 2.0 / Kling 3.0) and every property, person and number on the page is invented, as the brief allows.

## Run it

Open `index.html`, or serve the folder with any static host. On Vercel: import the repo, framework preset "Other", no build command, output directory `.`.

## What moves, and why

1. **The door.** The hero is a place you arrive at. Scrolling opens the inn's front door (forty keyed frames drawn to a canvas by scroll position) and pushes you through it into the next section. The doorway is a real hole: what you see through it is the page beneath.
2. **The money model.** In "Paid on results", one tracked booking prints line by line: what the guest paid, Autumn's 13%, what stays with the owner.

Everything else is feedback and reveal, tuned to finish inside the viewport and stay finished. Reduced motion gets static frames; phones get the plain hero.
