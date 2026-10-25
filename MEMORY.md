# Project Memory — Kurzgesagt Sun Vanished

## Design Stack Decision (locked)
- Frontend: Static HTML/CSS/JS on Vercel (current pipeline) + optional GSAP or CSS for subtle interactions.
- Motion: Continue pure seek(t) for video core; HyperFrames for rapid iterations; GSAP/Framer for site polish if needed.
- Icons: Phosphor Icons (phosphoricons.com)
- Gradients: Custom navy-to-indigo space gradients matching palette, inspired by feralui and Backgrounds.supply.
- Inspiration sources scanned: 60fps.design (spring physics, parallax, sequence), scrolltide.co (cinematic scroll, shaders), styles.refero.design (AI design systems), recraft.ai (vector), bencho.dev (React components).
- Visual direction: Dark space (#081d2c–#102348), teal/gold accents, film grain, vignette, no vanilla defaults. High production value, one-hero discipline.
- Pipeline: HyperFrames compose → analyze frames → refine prompt → 4-loop iterations. Local pure-code as deterministic fallback. Site embeds latest MP4.

Locked 2026-10-25.