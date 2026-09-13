Drop photos here with these exact names and they appear on the site automatically.
Any that are missing fall back to a dashed placeholder, so partial is fine.

- `ranger-hero.jpg` — the main shot. Landscape, 4:3-ish, at least 1600px wide.
- `pack.jpg` — battery pack / Tesla modules (not yet supplied)
- `motor.jpg` — Hyper9 + X1 inverter
- `dash.jpg`  — the CAN dashboard running

HEIC off an iPhone won't render in browsers. Convert first:
`sips -s format jpeg -Z 2000 IMG_1234.HEIC --out img/ranger-hero.jpg`
