# Attribution — Stride physio imagery fix (STRIDE-01 / STRIDE-02)

Images from [Pixabay](https://pixabay.com/). Free for commercial use; recorded for the Little demo Direct Upload drop-in.

| File | Pixabay ID | User | Page | md5 |
| --- | --- | --- | --- | --- |
| `assets/desk.jpg` | 6371695 | SpencerWing | https://pixabay.com/photos/resistance-bands-strength-training-6371695/ | `afea4190c4f232c15f247435bc57d86a` |
| `assets/marta.jpg` | 8564036 | innamykytas | https://pixabay.com/photos/fitness-exercise-woman-fit-8564036/ | `509287dff1cfb74e913ab889f80cba57` |
| `assets/devin.jpg` | 465202 | teamsmashgame | https://pixabay.com/photos/fitness-guy-black-exercise-465202/ | `b773cbc5a76836929ab6a4f3c0ffddcd` |
| `assets/priya.jpg` | 7539141 | u_us19rkvq | https://pixabay.com/photos/gym-woman-fitness-athleisure-7539141/ | `240b00a86f8f4c2d78b8ebe30625220e` |

## Details

### `assets/desk.jpg`
- **ID:** 6371695 — SpencerWing
- **Page:** https://pixabay.com/photos/resistance-bands-strength-training-6371695/
- **Source size:** 4240×2832 (Pixabay `largeImageURL`)
- **Local bytes / md5:** 255522 / `afea4190c4f232c15f247435bc57d86a`
- **Tags:** resistance bands, strength training, workout, physical therapy, home gym
- **Why it clears STRIDE-01:** Five loop resistance bands on a wooden assessment surface — physio kit visible. Not blank-iMac lifestyle; not office back-pain stock alone. No logos.

### `assets/marta.jpg`
- **ID:** 8564036 — innamykytas
- **Page:** https://pixabay.com/photos/fitness-exercise-woman-fit-8564036/
- **Source size:** 2500×3757
- **Local bytes / md5:** 148337 / `509287dff1cfb74e913ab889f80cba57`
- **Tags:** fitness, exercise, woman, resistance bands, weights, stretch, training
- **Why it clears STRIDE-02:** Athletic woman demonstrating resistance-band exercise therapy. No lab coat, no stethoscope, no clinic logos / Cyrillic.

### `assets/devin.jpg`
- **ID:** 465202 — teamsmashgame
- **Page:** https://pixabay.com/photos/fitness-guy-black-exercise-465202/
- **Source size:** 4912×7360
- **Local bytes / md5:** 264718 / `b773cbc5a76836929ab6a4f3c0ffddcd`
- **Tags:** fitness, trainer, gym, sports, exercise
- **Why it clears STRIDE-02:** Smiling athletic-trainer portrait in a gym / rehab context. No stethoscope, no lab coat, no embroidered foreign clinic logo (small Nike swoosh on shirt only — not a clinic brand).

### `assets/priya.jpg`
- **ID:** 7539141 — u_us19rkvq
- **Page:** https://pixabay.com/photos/gym-woman-fitness-athleisure-7539141/
- **Source size:** 3240×5760
- **Local bytes / md5:** 136763 / `240b00a86f8f4c2d78b8ebe30625220e`
- **Tags:** gym, woman, fitness, athleisure, workout, exercise
- **Why it clears STRIDE-02:** Athletic woman portrait with light dumbbells; sports-physio register. No lab coat, no stethoscope, no logos / Cyrillic.

## Notes
- Self-host under `/assets/` — CSP `img-src 'self'` only (no remote Pixabay URLs).
- Pack path: `/workspace/yulia/catalog-glance-2026-09-14/stride-imagery-fix/`
- Live hosts were **not** edited by this pass.
