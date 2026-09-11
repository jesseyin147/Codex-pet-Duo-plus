# Duo Plus look mechanics

Duo is a compact, soft-bodied pixel-art owl. The feet and lower belly stay anchored to the same baseline while the eyes lead attention, followed by a restrained head and upper-body turn. The orange beak remains attached at the center of the facial plane and shifts with the head; wings stay close to the body and follow slightly. Ear tufts and brow corners echo the head direction without changing the silhouette or scale.

## Motion budget

Each 22.5-degree step changes eye direction, eyelid shape, beak placement, and head/upper-body yaw or pitch by a small, even amount. Feet, lower belly, body height, and overall pixel density remain stable. No single step may introduce a large lateral jump, scale pop, or silhouette break.

## Cardinal pose families

- **000 up:** pupils and eye surfaces aim upward; upper eyelids lift; beak sits slightly higher; head pitches up while feet and lower belly remain fixed. More underside of the brow ridge is visible.
- **090 screen-right:** pupils, beak tip, and facial plane shift unmistakably toward the image's right edge. The left side of the face/body becomes slightly more visible; the right wing is modestly occluded.
- **180 down:** pupils and eye surfaces aim downward; upper lids lower slightly; beak sits lower; head and upper body bow while the feet remain fixed. More crown and brow surface is visible.
- **270 screen-left:** pupils, beak tip, and facial plane shift unmistakably toward the image's left edge. The right side of the face/body becomes slightly more visible; the left wing is modestly occluded.

## Continuity and identity locks

All 16 poses form one clockwise loop. Eye whites, pupils, highlights, eyelids, beak, face mask, belly markings, wings, feet, outline thickness, and green/orange palette remain the same construction as the source atlas. The large physical eyes rotate as complete eye surfaces with coordinated pupils and eyelids; pupils never float outside the white eye apertures. No whole-sprite rotation, detached marks, shadows, text, guide pixels, new props, or background elements.
