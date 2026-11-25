# Honey Elixir website (installable app)

Single-page bilingual site. Opens in **English**; the EN/ع button switches and the choice is
remembered on that device. The installed app always starts in English.

## Publish on GitHub Pages
1. Create a public repository, e.g. `honey-elixir`.
2. Upload every file in this folder to the repository root
   (index.html, manifest.webmanifest, sw.js and the four icon PNGs).
3. Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / root → Save.
4. After about a minute the site is live at `https://<your-username>.github.io/honey-elixir/`.

## Install as an app
Needs **https**, so GitHub Pages works and opening the file from a USB stick does not.

- **Chrome / Edge (Android, Windows, Mac):** an "Install app" button appears in the header and
  a bar at the bottom; Chrome also shows an install icon in the address bar.
- **iPhone / iPad (Safari):** Share → Add to Home Screen. Tapping the button shows these steps.
- Once installed it opens in its own window with the Honey Elixir icon, rotates with the phone,
  and works offline.

## After you change the site
Edit `index.html`, then bump the cache name in `sw.js` (`honey-v1` → `honey-v2`) so installed
copies pick up the new version.
