Photos for the site. Drop a file in with the right name and it appears automatically.
Anything missing falls back to a plate-number placeholder, so partial is fine.

MASTHEAD (full-bleed, behind the title)
- `finished.jpg`  — the finished truck. This wins if present.
- `founder.jpg`   — fallback used until `finished.jpg` exists.

BUILD SHEET
- `ranger-hero.jpg` — FIG. 00, engine coming out

PLATES (gallery)
- `motor.jpg`      — FIG. 01, Hyper9 on the adapter plate
- `drivetrain.jpg` — FIG. 02, motor + inverter going in
- `bay.jpg`        — FIG. 03, HV hardware in the engine bay
- `selector.jpg`   — FIG. 04, R/N/D selector in the dash
- `underneath.jpg` — FIG. 05, under the truck
- `dogs.jpg`       — FIG. 06, shop supervisors

Masthead photo should be landscape and at least 2000px wide — it runs edge to edge.

HEIC off an iPhone won't render in browsers. Convert first:
`sips -s format jpeg -Z 2400 IMG_1234.HEIC --out img/finished.jpg`
