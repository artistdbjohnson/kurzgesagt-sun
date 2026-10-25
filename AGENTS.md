# Motion Studio Rules (locked from Opus 5.5 lab)

## Render Contract
- One self-contained HTML.
- Every frame is a pure function of t: window.seek(t).
- No Date.now, setTimeout for motion, no unseeded Math.random.
- Dual clocks: ambientTime vs storyTime (supports rewind).
- Loops: frames 0 to N-1 only.
- ?t= query freezes exact frame for QA.

## Banned Defaults
- Outlines on Sun edge, flares, static strips, whole-text fades.
- Purple/blue gradients, glow orbs, neon, particles as decoration.

## Sensors
1. Contact sheet of every key beat.
2. Seam check.
3. Smoke test.
4. Frame-by-frame notes.

Nothing ships until sensors pass.