# Whole-device cutaway: coherent pillars and clean diameter section

The human identified a mismatch between the visible diameter section and the rear pillar array, plus irregular fragments on the left. The historical Boolean cut had 64 zero-area pillar faces on the left and eight 34-vertex section n-gons. The nominal source positions were already those of the radial array; the new version repairs the cut topology and makes the front and top explicitly derive from one clean extruded mesh.

![Repaired section](01_impact_section_v36_preview_white.png)

[Transparent cropped section](01_impact_section_v36_asset.png)

## Native geometry repair

All 98 triangular pillars retain the original four radial rings, nominal 3 mm triangle side, compression control and modest 0.25 mm bow. Each triangular XY profile is clipped analytically at the diameter before extrusion through 17 height rings. The section consists of small quads rather than long Boolean n-gons. There are four intersected pillars on each side, supplied by the same bodies that form the rear/top array. The left and right nominal arrays mirror within 0.0001 mm. The evaluated pillar mesh has zero open/nonmanifold edges and zero zero-area faces.

The invisible SSG cavity operand copies this exact mesh and its deformation drivers. Normal-directed 0.04 mm extensions cross the hidden top, bottom and diameter planes; the front extension is selected by both face orientation and y=0 position, so it cannot enlarge rear-facing interior side walls. Inspection also found that the historical Faces extrusion used its default 1 mm Offset Scale despite a labeled, unlinked 0.04 mm vector. This version explicitly sets the effective Offset Scale and does not inherit the old fill audit.

## Fresh filling verification

The current saved model was reopened and its evaluated geometry sampled between the base top and cover underside. All six fresh fill checks pass: 24,136 samples, zero missing-region samples and zero bulk-overlap samples beyond the unchanged 0.02 mm display contact tolerance. This tolerance covers tessellation and the retained 0.005 mm display skin separation; it is not a fabrication tolerance. The evaluated SSG surface is closed, with zero nonmanifold edges and zero zero-area faces.

All 28 native checks pass, including nominal source-position correspondence, front/top coherence, small valid cut faces, matching cavity drivers, fresh filling and preservation of the accepted scenes.

The main camera, materials, silicone base, cover, outer frame, rigid support, lights and impact controls remain unchanged. The two lower specimen scenes and separate orange impact cue have identical native snapshots and PNG bytes to V35.

## Matching impact cue retained

![Matching preview](05_impact_alignment_v36_preview_white.png)

[Whole section](01_impact_section_v36_aligned.png) and [orange cue](04_orange_impact_trail_v36_aligned.png) each use a 2400 x 1100 RGBA canvas. Overlay at identical size and origin. Cropped assets have different bounds. The combined image is an alignment preview, not an overall Figure 3 layout.

## Accepted closeups retained

![Central SSG response](02_SSG_response_contrast_v36_preview_white.png)

![Pillar interaction](03_pillar_context_v36_preview_white.png)

Native Blender illustration only. Deformation, filling appearance and response colors are qualitative; no physical solver or thermodynamic phase-field calculation was run. No rendered text or arrowheads, new Pro inquiry, source-document edit or local Git write. Only PNG renders and Markdown are published; the editable model and six-PNG archive remain local.

[Previous version](../panel_a_v35/MODEL_REVIEW.md)
