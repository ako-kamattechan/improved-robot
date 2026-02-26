# Semantic Compression: Relax / Constrain Demo (v0.1.0)

Single-file visualization of a control loop:

RELAX → CONSTRAIN → FRAME_SHIFT

- **RELAX** expands candidate space (exploration)
- **CONSTRAIN** projects onto a target structure (selection)
- **FRAME_SHIFT** (“not X, it’s Y”) swaps the target manifold
- Each action is recorded in a **Merkle-like lineage log** (tamper-evident chain)

## Run
Open `demo/semantic-compression-v0.1.0.html` in your browser.

## Hotkeys
- R: RELAX
- C: CONSTRAIN
- X: switch frame
- Space: idle
- Enter: reset
