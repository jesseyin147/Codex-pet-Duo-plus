Create one horizontal animation strip for Codex pet `duo-plus`, state `waving`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 4 full-body frames in one left-to-right row on flat pure cyan #00FFFF. Treat the row as 4 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Preserve the downloaded Duo identity: compact bright-green owl, rounded body, orange beak and feet, large expressive white eyes, bold clean Codex pet sprite style. Improve expressiveness with natural head, eye, eyelid, brow, wing, and upper-body motion; retain the same palette and silhouette.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Faithfully preserve the existing atlas style and identity; crisp clean sprite rendering readable at 192x208..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Greeting loop: paw or limb down, raised, tilted, and returning in a friendly attention gesture.

Vividness direction: stage a warm four-beat greeting—anticipation lean, wing raised high, cheerful peak with bright eyes, and return—with clear wing silhouette changes and a small opposite-side body counter-lean.

AUTHORITATIVE SIMPLE MOTION FLOW — WAVING: Duo enthusiastically flaps both wings up and down like flying while staying in place.

Use `selected poses/waving.png` as the exact acting target for the wings-up pose. Frames: (1) both wings lowered beside the body and a slight anticipation crouch; (2) both wings spread outward at mid-height as the body rises; (3) both wings high above the shoulders in the reference silhouette, bright eyes and cheerful open beak; (4) both wings sweep back down as the body settles.

Both wings move together in a clear down → middle → high → down cycle. This is a synchronized stationary flying-style flap, not a one-wing hand wave or alternating wings. Keep both feet visible and planted. Do not copy the fire, red background, or detached marks.

State requirements:
- Show the greeting through paw, hand, wing, or limb pose only.
- Do not draw wave marks, motion arcs, lines, sparkles, symbols, or floating effects around the gesture.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.
