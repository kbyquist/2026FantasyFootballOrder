# Fantasy Football Draft Lottery

A zero-build static web app that uses the MLB Stats API to live-update the fantasy football draft order.

## Rules
1. Runs scored — most is best.
2. Hits — first tiebreaker.
3. Runs allowed — second tiebreaker; fewer is better.

## Assigned teams
Andrew — Orioles  
Connor — Diamondbacks  
Derek — Royals  
Hannan — Giants  
Kasey — Brewers  
Kory — Mariners  
Logan — Rangers  
Patrick — Marlins  
Tania — Guardians  
Tyler O — Yankees  
Will — Braves  
Tyler H — Padres

## Run locally
Open `index.html` in a browser, or serve the folder with any static web server.

## Deploy
This is static HTML/CSS/JS, so it can be deployed directly to Vercel, Netlify, GitHub Pages, Cloudflare Pages, etc. No backend is required.

The app polls MLB's public Stats API every 15 seconds and refreshes the board automatically.

The draft date is set to `2026-08-26` in `index.html` so the page remains tied to the baseball games used for this draft lottery.
