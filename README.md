# Unplugged

Unplugged is a small web app for tracking daily habits, starting with the days you don't use your phone. Each day you tick a habit off, and the ticks join into a chain so you can see your streak build.

- **Today screen** lists every habit with a one-tap tick button and a 14-day chain. Links between days only light up when the days are consecutive
- **Perfect days:** a summary card shows how many habits you've done today, and counts a streak of days where you ticked them all
- **Each habit has its own colour** (8 to choose from), which themes its card and its own screen
- **Habit screen** with a big streak number, longest chain, total days, this month's %, an 18-week grid, milestones (3, 7, 14, 21, 30, 60, 100, 180 days, 1 year) and a calendar where you can tick or untick past days
- **Add, edit or delete habits:** tap **＋** to pick a suggestion or type your own; the pencil on a habit's screen edits it
- **Confetti and messages** when you tick, hit a milestone, or have a perfect day
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
