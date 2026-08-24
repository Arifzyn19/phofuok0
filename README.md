# AquaSpace — Fish Tank Stocking Calculator 🐠

Single-page aquarium stocking tool — cek kapasitas tank biar ikan nggak overcrowded.

**Live demo (GitHub Pages):** `https://Arifzyn19.github.io/phofuok0/` *(aktif setelah Actions deploy)*

## Features
- Input tank size (gallons) dengan stepper + slider
- 5 fish presets sebagai clickable cards (Goldfish 10 gal, Guppy 1 gal, Betta 5 gal, Neon Tetra 2 gal, Angelfish 10 gal)
- Add flow: pick species → set quantity → Add (merge jika species sama)
- Running list dengan remove per row
- Live capacity bar: hijau <80%, kuning 80-100%, merah >100% + animasi
- Summary text: `Your 20-gallon tank can fit 3 more Neon Tetras` / `⚠️ Overstocked by 5 gallons!`
- Icon **Lucide** full (fish, droplets, gauge, sparkles, dsb) — no emoji
- No backend, no auth, state di page saja

## Run Local
```bash
# buka langsung
open index.html
# atau
npx serve .
```

## Deploy
Push ke `main` auto-deploy via GitHub Actions → GitHub Pages.

## Tech
Vanilla HTML/CSS/JS single file + Lucide CDN, Google Fonts (Nunito + Inter).
