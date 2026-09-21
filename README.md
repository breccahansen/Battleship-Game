# Battleship-Game

AI driven online Battleship game — a single-page web app (plain HTML/CSS/JS, no build step).

**Play now:** https://battleship-qtkviglj.devinapps.com

## How to play
1. Place your five ships on **Your Fleet** (click to place, `R` or *Rotate* to change orientation, or *Random Placement*).
2. Choose an AI difficulty (Easy / Normal / Hard) and click **Start Battle**.
3. Click cells in **Enemy Waters** to fire. `✕` = hit, `●` = miss. Sink all five enemy ships before the AI sinks yours.

## Running locally
Open `index.html` in any browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Hosting
Any static host works (GitHub Pages, Netlify, Vercel, etc.) — just serve `index.html`.
