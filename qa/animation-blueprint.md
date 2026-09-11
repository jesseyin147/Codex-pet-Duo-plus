# Duo Plus animation blueprint

## Visual contract

- Preserve the compact pixel-art Duo identity from `references/canonical-base.png`: bright-green owl, large white eyes, orange beak and feet, green belly marks, and dark pixel outline.
- Treat the files in `selected poses/` as **acting references only**. Do not copy their gradient backgrounds, crop, anti-aliased rendering, flames, yellow emphasis marks, or altered proportions.
- Every frame is a complete, centered, full-body pet in a `192x208` cell. Keep scale and baseline stable except during the jump.
- Motion is conveyed through the body, face, wings, feet, and pose. No detached effects, symbols, shadows, scenery, motion lines, or text.
- Use strong key poses, readable anticipation, small follow-through, and matching first/last poses for clean loops.

## Row 0 — idle, 6 frames

Purpose: lively but unobtrusive baseline.

1. Neutral upright pose, eyes open.
2. Chest expands two pixels; ear tufts lift slightly.
3. Soft half-blink; wings settle inward.
4. Full blink with a tiny downward squash.
5. Eyes reopen; one ear tuft rebounds and body rises.
6. Return almost exactly to frame 1.

Timing: relaxed and even, with frames 1 and 6 held slightly longer. Feet remain planted.

## Row 1 — running-right, 8 frames

Purpose: energetic screen-right drag motion.

1. Low anticipation, weight on rear foot.
2. Right-facing push-off; head leads.
3. Passing pose with body rising and wings counter-swinging.
4. Longest readable stride; front foot reaches right.
5. Soft contact and body squash.
6. Opposite-foot push-off.
7. Second passing pose.
8. Return toward frame 1 with alternating feet preserved.

Timing: quick, springy two-step cadence; no speed lines or dust.

## Row 2 — running-left, 8 frames

Use the same cadence as running-right while facing and travelling screen-left. A deterministic framewise mirror is acceptable only if the newly generated right-facing row contains no asymmetric markings or props.

## Row 3 — waving, 4 frames

Key reference: `selected poses/waving.png`.

1. Friendly anticipation lean; both wings begin to open.
2. Wings raised broadly, with the screen-left wing slightly higher.
3. Peak enthusiastic greeting inspired by the reference: both wings high, bright eyes, open cheerful beak, and a small upward stretch.
4. Wings lower toward neutral with a soft opposite-side counter-lean, ready to loop.

Do not reproduce the fire, red background, or any detached accent. Keep both feet visible throughout.

## Row 4 — jumping, 5 frames

1. Deep anticipation squash, wings down.
2. Fast lift with legs extending and wings opening.
3. Airborne peak: tallest stretch, joyful eyes, wings high.
4. Descent with wings cushioning and feet preparing to land.
5. Soft landing squash that can flow back to frame 1.

No floor shadow, landing burst, dust, or detached effects.

## Row 5 — failed, 8 frames

Key reference: `selected poses/failed.png`.

1. Neutral focused pose.
2. Eyes widen and body stiffens at the setback.
3. Brows descend; wings begin folding inward.
4. Wings cross firmly over the belly, borrowing the reference silhouette.
5. Peak frustrated pose: crossed wings, narrowed eyes, head slightly lowered.
6. Hold the crossed-wing pose with a small exhale squash.
7. Eyes soften; wings loosen but remain inward.
8. Recover toward the focused starting pose without becoming cheerful.

Remove the red gradient background. Keep the reaction sympathetic, readable, and full-body; no red X or detached tear.

## Row 6 — waiting, 6 frames

Key reference: `selected poses/waiting.png`.

1. Upright attentive pose.
2. Slow side glance with one brow lifting.
3. Head tilts; one wing rises toward the cheek.
4. Peak impatient/bored pose from the reference: half-lidded eyes and wing resting against the cheek, feet planted.
5. Small sigh-like body drop; eyes briefly close.
6. Return to an alert, hopeful center pose.

Remove the blue gradient background. The loop should clearly mean “waiting for input,” not failure or ordinary idle.

## Row 7 — running/working, 6 frames

Purpose: active processing without literal travel.

1. Focused upright pose.
2. Eyes scan screen-left; wings make a small attached gesture.
3. Eyes cross through center; body rises with concentration.
4. Eyes scan screen-right; opposite wing answers.
5. Brows lift as if reaching a result; body gives a contained bounce.
6. Return to focused frame 1.

Feet remain planted. No typing prop, UI, icons, or directional running.

## Row 8 — review/completion, 6 frames

Key reference: `selected poses/finished running.png`.

1. Focused inspection lean with narrowed eyes.
2. Head tilts to check the result; one wing touches the cheek.
3. Eyes brighten and body begins to rise.
4. Peak completion pose inspired by the reference: wide happy eyes, open cheerful beak, both wings lifted, and a compact upward stretch.
5. Pleased settling bounce with wings lowering.
6. Confident upright finish that loops naturally to inspection.

Do not reproduce the blue background or floating yellow marks. Keep the whole body and feet visible.

## Rows 9–10 — 16 look directions

Use `qa/look-mechanics.md`. Eyes lead, followed by beak, head, brow, ear tufts, and restrained upper-body yaw/pitch; feet and lower belly stay anchored. Preserve the fixed clockwise order and unmistakable cardinals.
