# Cotton On Foundation Website Mockup

An immersive one-page website mockup for a Cotton On Foundation launch experience called **Where Good Takes Root**.

The site is designed as a vertical sensory journey through a biophilic sanctuary at dusk. Guests begin at a planted threshold, move through the Foundation pillars of Learning, Wellbeing, and Green Cities, then arrive at a launch tee reveal and give-back exit. The visual world is intentionally dark, warm, and botanical: moss, canopy light, soft amber highlights, realistic section renderings, and an ambient soundtrack support the feeling of entering a living indoor garden rather than a standard campaign page.

## Concept

The experience keeps the Cotton On Foundation work at the centre. The T-shirt appears late in the journey as the final lift, not the opening sales message. Each floorplan zone connects to sensory cues so the mockup explains how the real launch space could feel in person: light, sound, scent, texture, and taste.

Key ideas:

- A dusk-to-glow scroll narrative that blends between scenes instead of feeling like separate slides.
- A realistic, to-scale floorplan for a 30.0 m by 18.0 m reception floor.
- Clickable floorplan sections with animated rendering previews and sensory notes.
- A launch-day countdown styled as an overgrown botanical timepiece.
- A foundation-forward tee reveal with the launch product treated as a quiet, meaningful crescendo.

## Project Structure

- `cotton-on-foundation-launch-experience.html` - the full static website.
- `assets/images/` - hero imagery, zone renderings, and T-shirt artwork.
- `assets/music/` - the background soundtrack.

## Run Locally

Use any static server from the repo root:

```bash
python -m http.server 4173
```

Then open:

```text
http://localhost:4173/cotton-on-foundation-launch-experience.html
```

## Update Launch Countdown

Edit the `data-launch` value on `#launchCountdown` inside `cotton-on-foundation-launch-experience.html`.

Use ISO date format with Singapore timezone, for example:

```html
data-launch="2026-11-21T19:00:00+08:00"
```
