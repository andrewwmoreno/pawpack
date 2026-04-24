# PawPack Landing Page — Asset Manifest

This landing page mirrors the structural flow of bureo.co (hero → "difference" pillars → material story → 6-step process → stats → personas → FAQ → next-up → footer) with all content, copy, and palette swapped to PawPack.

The current build uses **two real PawPack assets** (`logo-mark.png`, `wordmark.png`) and **procedurally-generated SVG illustrations** in every other visual slot. The SVGs are production-usable, but for a final marketing site you'll want to replace them with real photography and video. Below is the full asset list, grouped by section and sized to match the layout.

---

## Brand assets (in use)

| Slot | File | Status |
|---|---|---|
| Nav + footer logo mark | `assets/logo-mark.png` | ✅ Provided (Logo.png) |
| Nav + footer wordmark | `assets/wordmark.png` | ✅ Provided (Written_Name.png) |

## Hero section

| Slot | What's needed | Format | Suggested size |
|---|---|---|---|
| Hero background video *(optional loop)* | Slow-motion shot of a climbing rope uncoiling / a dog running on singletrack with the leash trailing | MP4, H.264, silent | 1920×1080, 10–15 sec loop, <5 MB |
| Hero key photograph | Hero dog + leash product shot, low light, mountain horizon | JPG | 1200×1600 (3:4 portrait) |
| Hero caption pill | "Rated 22 kN on the wall" — kept as text overlay | — | — |

Currently rendered as a custom SVG scene (night sky + mountains + stylized rope + paw print). Replace `.hero-visual > svg` with an `<img>` or `<video>` tag when final media is ready.

## "The Difference" section (4 pillars)

| Slot | What's needed | Format |
|---|---|---|
| Pillar 1 icon — "100% Retired Climbing Rope" | Line icon: rope coil or climbing carabiner | SVG, 48×48, 1.5px stroke |
| Pillar 2 icon — "Fully Traceable Provenance" | Line icon: checkmark in circle or QR dot pattern | SVG, 48×48 |
| Pillar 3 icon — "Zero Waste Manufacturing" | Line icon: circular arrow / closed-loop | SVG, 48×48 |
| Pillar 4 icon — "Built for the Actual Trail" | Line icon: compass or pawprint on contour | SVG, 48×48 |

Currently rendered as inline SVG. Icons should all share stroke weight and style — ideally a single designer-drawn set.

## Material / story section

| Slot | What's needed | Format | Suggested size |
|---|---|---|---|
| Coiled rope hero shot | Overhead macro of a neatly coiled retired climbing rope on concrete or wood workshop surface — the dynamic rope "character" is central to the brand | JPG | 1200×1500 (4:5 portrait) |

Currently rendered as SVG concentric rope coils.

## Process / "How It's Made" — 6 steps

Each step needs a **16:10 photograph or short video clip** showing that step authentically. This is the most asset-hungry section of the site.

| # | Step | What to capture |
|---|---|---|
| 01 | Sourcing | Rope handoff at a climbing gym — coiled retired ropes bundled at a gym front desk |
| 02 | Intake | Workshop inspection — rope being logged / photographed / tagged with provenance card |
| 03 | Sheath & Core separation | Close-up hands stripping the white nylon core from the braided outer sheath |
| 04 | Cutting | Rope being measured and cut to leash length on a workshop bench |
| 05 | Assembly | Solid brass clasp being attached by hand; stitching detail |
| 06 | To Your Door | Finished leash coiled in compostable kraft box, handwritten note visible |

**Ideal format:** Each as a 5–8 sec silent MP4 loop (mimicking the Bureo step-card hover behavior). Fallback: high-res JPG at 1600×1000.

## Stats section

No imagery. Just typography and the navy background. The counter at the top of the page (`1,247 meters of rope rescued`) animates on load — update the number in the script and in the stat card together.

## Personas section

| Slot | What's needed | Format |
|---|---|---|
| *(Optional)* Persona portrait for each of the 3 cards | Candid lifestyle shots: Maya (climber at gym w/ dog), Connor (weekend hiker at trailhead), Ava (first-time owner in urban park) | JPG, 800×1000 portrait, softly desaturated to match navy palette |

Currently rendered as text-only cards on navy. Adding photos would increase emotional resonance but is not required.

## FAQ section

No imagery needed — type-only.

## Next Up / subscribe CTA

| Slot | What's needed | Format |
|---|---|---|
| Square visual | A figure-8 climbing knot photograph, rope on neutral background | JPG, 1000×1000 square |

Currently rendered as a stylized SVG figure-8 knot.

## Footer

No imagery beyond the wordmark (already placed).

---

## Favicon + meta

For production deploy, add:

- `favicon.ico` — 32×32 PawPack paw mark on cream
- `favicon.svg` — vector version of the circular `p` monogram
- `apple-touch-icon.png` — 180×180 paw mark on navy
- `og-image.jpg` — 1200×630 with hero image + wordmark for social sharing

---

## Summary of counts

| Asset type | Count |
|---|---|
| Brand marks (done) | 2 |
| Hero photo/video | 1–2 |
| Feature icons | 4 |
| Lifestyle / story photos | 1 |
| Process step videos or photos | 6 |
| Persona portraits *(optional)* | 3 |
| CTA square visual | 1 |
| Favicon / social set | 4 |
| **Total new assets to source** | **19–22** |

All text, headlines, and copy are already in place — styled to your brand voice and pulled from the brand strategy document (purpose, promise, positioning, emotional benefits). Swap the visuals at your own pace; the page reads as complete in the meantime thanks to the SVG placeholders.
