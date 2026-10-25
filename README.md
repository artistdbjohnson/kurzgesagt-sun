# Kurzgesagt-style "What if the Sun vanished?" Video Generator

Pure code-drawn 1920x1080 30fps animation ready for YouTube.

## Files
- `index.html` — single file with `window.seek(t)` pure function of time.
- `render.py` — Playwright + ffmpeg pipeline.
- `contact_sheet.py` — beat grid for review.
- `output/sun_vanished_hyperframes.mp4` — completed HyperFrames render.
- `AGENTS.md` / `RULES.md` / `HARNESS.md` — locked render contract and sensors.
- `tools.md` — HyperFrames, mg-styles-15, awesome-ai-motion, Kokoro, Grok Imagine.
- `PROMPTS_GROK_IMAGINE.md` — broadcast-level reference prompts.

## Setup
```bash
pip install playwright pillow
playwright install chromium
python contact_sheet.py
python render.py
```

HyperFrames project completed. Local pure-code engine ready for iteration.

## Handoff
Broadcast team: use the MP4 or regenerate locally. Voice via Kokoro. Thumbs via Grok Imagine prompts.