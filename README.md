### Run locally
Download `demo/semantic-compression-v0.1.0.html` and open it directly in your browser.
(Some platforms block inline scripts in previews.)

It’s a single-file HTML demo that visualizes a simple control loop:

RELAX → CONSTRAIN → FRAME_SHIFT

- RELAX expands a candidate space (exploration)
- CONSTRAIN projects candidates onto a target structure (selection)
- FRAME_SHIFT (“not X, it’s Y”) swaps the target manifold
- Each action is recorded in a Merkle-like lineage log (tamper-evident history)

This is a small concept proof to explore how novelty and stability can coexist
when iterating over evolving artifacts.

**Run:**  
Open `demo/semantic-compression-v0.1.0.html` in any modern browser.

No build step, no dependencies.
