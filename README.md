# Kimbe Bay Hotel — demo website

**Demo only. Sample content. No backend.** Built to show what the hotel's website could look like.

- **Live:** https://dmagbual102970.github.io/Kimbe-Bay-Hotel/
- **Theme:** forest green · logo: KB monogram emblem · matching favicon
- **Hero:** sample coastal photograph (replace with the hotel's own photo)
- **Contact:** +675 983 5001 · WhatsApp · Kimbe, West New Britain Province
- **Demo content:** sample rooms (Standard K450, Garden K550, Family K650), services with photos,
  "why book direct", sample policies, guest stories.
- **Demo booking:** booking wizard, availability and "find my booking" work locally (no Firebase).

## Rebuilding

```bash
cd "Edgewood Hotel & Apartment/website"
VITE_DEMO_CONTENT=true node ./node_modules/vite/bin/vite.js build --base=/Kimbe-Bay-Hotel/
```

Copy `dist/` here, copy `index.html` to `404.html`, keep `.nojekyll`.
