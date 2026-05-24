## Goal
Replace the AI-generated images currently used across the site with real, free-to-use gym/fitness photos from Unsplash (licensed for commercial use, no attribution required).

## What changes

Update the image sources for these existing assets, keeping all component code, layout, and theme (black + orange) untouched:

- `src/assets/hero.jpg` — cinematic dark gym / athlete shot
- `src/assets/about.jpg` — gym interior / trainer with member
- `src/assets/service-strength.jpg` — barbell / deadlift
- `src/assets/service-cardio.jpg` — treadmills / cardio zone
- `src/assets/service-personal.jpg` — trainer coaching client
- `src/assets/service-weightloss.jpg` — HIIT / fat-loss training
- `src/assets/service-functional.jpg` — functional / kettlebell training
- `src/assets/transform-1.jpg` … `transform-4.jpg` — fit physique / workout shots

## How

1. Download high-resolution Unsplash photos (curated for dark, premium gym aesthetic) directly into `src/assets/`, overwriting the existing files.
2. Keep filenames identical so no component imports change.
3. Verify in the preview that each section renders the new photo correctly.

## Out of scope
- No layout, copy, color, or component changes.
- No new dependencies.

If you'd rather upload your own gym photos instead, let me know and I'll wire those in instead of Unsplash.