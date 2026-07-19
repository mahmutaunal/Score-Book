# Store Assets

These marketing images were composed from real application screenshots for use in store listings, project documentation, and press materials.

## Output Sets

- `android/en` — English store images
- `android/tr` — Turkish store images
- Resolution: `1080 × 1920 px`
- Format: RGB PNG
- Recommended order: dashboard, game catalog, live scorekeeping, result, settings

Original screenshots without marketing copy are available under `assets/screenshots/android`.

## Regenerating the Assets

Replace the original screenshots while preserving their file names, then run:

```bash
python3 -m pip install Pillow
python3 tool/generate_store_assets.py
```

The generator recreates both localized output sets.
