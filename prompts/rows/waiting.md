Create one horizontal animation strip for Codex pet `duo-plus`, state `waiting`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure cyan #00FFFF. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Preserve the downloaded Duo identity: compact bright-green owl, rounded body, orange beak and feet, large expressive white eyes, bold clean Codex pet sprite style. Improve expressiveness with natural head, eye, eyelid, brow, wing, and upper-body motion; retain the same palette and silhouette.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `auto`: Infer the most appropriate pet-safe style from the user request and reference images, then keep that exact style consistent across every row. User style notes: Faithfully preserve the existing atlas style and identity; crisp clean sprite rendering readable at 192x208..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Needs-input loop: expectant asking pose for approval, help, or user input.

Vividness direction: make the request readable through bright expectant eyes, alternating head tilts, a modest open-wing asking gesture, and a patient settle back to center. It should feel attentive and hopeful rather than idle.

AUTHORITATIVE SIMPLE MOTION FLOW — WAITING: Duo puts one wing under its chin and looks impatient.

Use `selected poses/waiting.png` as the exact acting target. Frames: (1) neutral Duo, eyes open, wings down; (2) eyelids lower halfway and eyes glance sideways; (3) one wing rises toward the underside of the beak/chin; (4) hold the wing-supporting-chin reference pose with half-lidded impatient eyes; (5) keep the chin-rest pose and shift the eyes to the opposite side; (6) lower the wing and return to neutral.

The wing must visibly contact and support the chin/beak area. Do not substitute a cheek touch, open-wing asking gesture, hopeful expression, sigh, or sadness. Remove the blue background and keep the full body visible.

State requirements:
- Show that Codex needs approval, help, or user input through an expectant asking pose.
- Keep the motion patient and readable, without turning it into ordinary idle or review.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.
