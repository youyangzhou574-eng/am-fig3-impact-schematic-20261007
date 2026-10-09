# Downward-motion effect on the simplified impact apparatus

The lower blue impactor stays sharp. Two faint earlier-position echoes lie above it and become progressively fainter, with two short blue streaks fading upward. This is a static visual cue for downward motion, requested by the human for the impact-experiment illustration.

![Downward impact schematic](01_downward_impact_experiment_v03_preview_white.png)

[Transparent PNG](01_downward_impact_experiment_v03_asset.png) · [Full 2000 x 1700 RGBA canvas](01_downward_impact_experiment_v03_full_canvas.png)

The native Blender apparatus from B02 is retained: saturated blue head, dark rear force sensor, pale simplified frame, gray support and the complete layered circular specimen. Its native shader graphs, studio lights and frontal camera are unchanged and continue to match panel a. There is no computer, external signal cable, rendered text or arrowhead.

## Native motion graphic

Only the blue head is echoed, at illustrative 8 and 16 mm higher local positions with 16% and 6% shader opacity. The annotations are positioned behind the actual head and sensor so their contours remain clear. Two slender native streak meshes have smoothly bounded opacity and fade toward the upper end. The graphical cues are camera-only and cast no shadows or secondary-ray effects.

The sharp apparatus and cues render into separate native view layers. A 3 pixel compositor blur softens only the cue RGBA; the original apparatus is composited directly in front. The native model remains editable. These positions and opacities are drawing parameters, not measured dynamics, velocities or experimental time samples. This deliverable is a still image with motion cues, not an animation or physical simulation.

## Verification and scientific scope

All 24 fresh native checks pass after reopening B02 and B03. The original object geometry, material graphs, camera, lights, world, pose, ray visibility and render settings compare exactly. Only four graphical meshes are added. Separate checks cover the cue positions, descending opacity, camera-only ray flags, softly bounded streaks and compositing order.

The exact retained specimen geometry inherits B02's 28 passing checks, including the 74 mm diameter, 6 mm total thickness, 1/4.5/0.5 mm layers, closed mesh volumes and SSG-plus-pillar enclosure volume. No new fill sampling or physical computation is claimed in this revision. The manuscript's 370 g mass and 10/20/30 cm release heights remain metadata; the drawn near-contact 14 mm gap is an illustration parameter, not a release height. The force sensor remains on the rear of the impactor according to the manuscript.

No new Pro inquiry, local Git write or original-document edit. Only PNGs and Markdown are published; native models and local receipts are excluded from the browser review repository.

[Original simplified apparatus](../panel_b_v02/MODEL_REVIEW.md) · [Retained panel a](../panel_a_v37/MODEL_REVIEW.md) · [Primary-source apparatus audit](../panel_b_v01/MODEL_REVIEW.md)
