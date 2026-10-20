# Unplugged

Unplugged is a small web app for tracking daily habits, starting with the days you don't use your phone. Each day you tick a habit off, and the ticks join into a chain so you can see your streak build.

- **Multiple habits**, each with its own icon, colour theme, streak, calendar and milestones. Switch between them with the chips at the top, which also show what you've ticked today. Add a habit with **＋ New habit**, or edit or delete one with the pencil
- **Big streak counter** with a progress ring that fills toward your next milestone
- **One-tap tick** for today, with confetti; tap again to undo
- **Calendar** where consecutive ticks join into one continuous bar. Tap any past day to fix it, and swipe to change months
- **Milestones** at 3, 7, 14, 21, 30, 60 and 100 days, and 1 year
- **Stats:** best streak, total days, and this month's %
- **Works offline** and installs to your iPhone home screen
- **Back up / Restore** all habits to a JSON file (your data lives only on your device)

There is no build step and no dependencies. It is just `index.html`, a service worker and a manifest.

## Use it on your iPhone

1. Host it. The included workflow deploys to **GitHub Pages**: in the repo go to *Settings → Pages → Source: GitHub Actions*, then push. The site appears at `https://<user>.github.io/<repo>/`. Any static host works too (Netlify, Vercel, Cloudflare Pages).
2. Open that URL in **Safari** on your iPhone.
3. Tap **Share → Add to Home Screen**. It opens full-screen like a native app and works offline.

Tap **Back up** now and then to save a copy of your data to Files.

## Run locally

```sh
npx http-server .
```
