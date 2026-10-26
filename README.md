# AutoMix Studio

AI mixing and mastering in the browser. Drop in your multitracks, press **AUTO MIX**, and export a finished MP3 or WAV.

![AutoMix Studio mixer](assets/mixer.jpg)

## What it does
- Recognises each instrument and builds a full chain: clean-up (denoise, gate, de-ess, hum), EQ, compression, reverb and delay
- Pans doubled parts left and right, puts the lead vocal on top, tames room mics
- 20 mix styles (Pop, Rock, Metal, Hip-Hop, Trap, EDM, Mizrahi, Jazz …)
- Mastering to a loudness target (Spotify −14, Apple Music −16, Loud −11, Club −9)
- Opens Cubase (.dawproject), Ableton Live (.als), Logic Pro and Pro Tools (AAF) sessions, and sends processed tracks back

## Files
| File | What it is |
|---|---|
| `index.html` | Landing page |
| `app.html` | The app — one self-contained file |
| `assets/` | Screenshots used by the landing page |

## Publish with GitHub Pages
1. Upload all files in this folder to the root of a new repository (keep `assets/` as a folder).
2. **Settings › Pages** → *Source: Deploy from a branch* → branch `main`, folder `/ (root)` → **Save**.
3. After a minute the site is live at `https://<your-user>.github.io/<repo>/` — the landing page, with the app at `/app.html`.

## Run locally
Open `app.html` in Chrome or Edge. Everything runs in the browser; audio never leaves your computer.

© 2026 AD SOUND & SERVICE
