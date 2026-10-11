# R6 II Settings (PWA)
Open index.html; all presets live in the `PRESET DATA` script block at the top.
- New condition: add `{id, name, ev, tip}` to CONDITIONS. `ev` = scene brightness at ISO 100 (sun 15, overcast 12, shade 9, dusk 10, indoor 5-8). ISO is calculated automatically.
- New subject: copy an entry in SUBJECTS and edit `photo` (shutter/minShutter in seconds, aperture >= 4, drive, ibis), `video` (res, is) and `af` (servo, detect, eye, area, case, pre).
- Lens change: edit GEAR.maxAperture.
- After editing, bump the cache name in sw.js (r6s-v1 -> r6s-v2) so phones pick up the update.
