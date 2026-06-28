# Cotton On Foundation Website Mockup

An immersive static website mockup for a Cotton On Foundation launch experience, built as a scroll-led biophilic sanctuary with sensory navigation, ambient audio, a launch-day countdown, floorplan interactions, and realistic section renderings.

## Project Structure

- `cotton-on-foundation-launch-experience.html` - the full static site.
- `assets/images/` - hero imagery, zone renderings, and T-shirt artwork.
- `assets/music/` - background soundtrack.
- `vercel.json` - rewrites the Vercel root URL to the experience page.

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

## Deploy To Vercel

1. Push the latest repo changes to GitHub.
2. Go to [Vercel](https://vercel.com/) and choose **Add New Project**.
3. Import `Chi944/CottonOn-website-mockup`.
4. Use **Other** as the framework preset.
5. Leave the build command empty.
6. Leave the output directory as `.`.
7. Click **Deploy**.

The included `vercel.json` makes the Vercel root path open the experience automatically.

## References

- [Vercel build settings](https://vercel.com/docs/builds/configure-a-build)
- [Deploying GitHub projects with Vercel](https://vercel.com/docs/git/vercel-for-github)
