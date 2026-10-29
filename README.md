# Zouie

Portfolio for Zouie, Roblox Studio builder. Static site: `index.html` plus `images/`.
All copy is taken verbatim from the original Google Sites page (https://sites.google.com/view/zouie/home).

## Run locally
```bash
python3 -m http.server 4710
```
Open http://localhost:4710.

## Design
Neo-brutalist: cream grid paper, thick black borders, hard offset shadows, yellow accent; Space Grotesk +
Silkscreen pixel. Big count-up stat tiles (+5 / 05 / 38), a scrolling marquee, scroll-reveal, and a scrolling
reviews band. The reviews are PLACEHOLDERS (tagged "Sample") — replace with real client quotes before relying
on them. Honours prefers-reduced-motion.

## Projects
Two slideshows (24 + 14 = all 38 original carousel images), each slide titled by its original caption;
game shots show the game name. Crossfade, idle zoom, progress bar, filmstrip, arrows, keyboard and swipe.
17 of the 38 were screen-captured from the live carousel (~786px) and are a little softer than the other 21.

## Deploy
On Vercel from the `main` branch; every push redeploys.
