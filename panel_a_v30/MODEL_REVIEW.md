# Frontal whole section and separate registered orange impact trail

The human requests a new whole-device view with the section facing the observer, a separate orange square downward motion trail fitting the central depression, and an explicit check that the enclosed section is fully filled with SSG.

![Frontal whole-device section](01_impact_section_v30_preview_white.png)

[Whole section transparent PNG](01_impact_section_v30_asset.png)

The native diameter-cut model now has zero camera yaw and roll, with a mild 18-degree downward view to reveal its depth. The original specimen meshes, shape keys, indentation, shaders and lights are retained. The old narrow arrow is unlinked. There is no rendered text or impactor mass.

![Separate orange square downward trail](04_orange_impact_trail_v30_preview_white.png)

[Separate orange trail PNG](04_orange_impact_trail_v30_asset.png)

The orange trail is a fourth independent native scene containing a camera-facing square gradient sheet. Its lower flat edge is strong orange and its upper portion fades to transparency; it has no triangular arrowhead or solid mass. Its 16 mm projected width matches the 16 mm central flat indentation span, and its 16 mm screen-plane height gives a square profile. The bottom clears the central cover by 0.10 mm, equivalent to 2.72 pixels at delivery resolution. These dimensions define a qualitative loading annotation, not a measured impactor.

## Exactly registered overlay pair

![Alignment preview only](05_impact_alignment_v30_preview_white.png)

[Full-canvas whole section](01_impact_section_v30_aligned.png) and [full-canvas orange trail](04_orange_impact_trail_v30_aligned.png) are both 2400 x 1100 RGBA PNGs. Overlay them at the same size and origin for exact registration. The projected contact width and the square are each 457.14 pixels. The cropped individual assets are convenient stand-alone elements but have different crop bounds. This matching preview is not an overall Figure 3 layout.

## SSG filling audit and native repair

The historical whole-view SSG Boolean had 147 open boundary edges and one additional nonmanifold edge. The cavity operation now uses a closed-manifold solver. A native Geometry Nodes modifier extends only the hidden cutter endpoint caps by 0.04 mm through the enclosure skins, avoiding coplanar membrane fragments. The visible pillars and their side interfaces are preserved, and the invisible cutter retains its source mesh and shape-key drivers.

Generated Boolean/Extrude vertices initially lost the existing color attribute, producing 9,009 zero-RGB entries and a black patch despite filled geometry. A native named-attribute field now restores the original radial pale/central palette on evaluated vertices. The source colors, all shader graphs and geometry coordinates remain unchanged; there are zero missing black color entries after reopening. No bitmap mask or painted image patch is used.

The actual evaluated SSG mesh now has zero nonmanifold edges. 24,136 sample points were checked across the diameter section and the enclosed 3D interior, using three-direction odd/even ray intersections between the base top and cover underside. No missing or bulk-overlap samples remain outside the 0.02 mm near-contact display tolerance, which accommodates tessellation and the established 0.005 mm rendering skin separation. This tolerance is not a fabrication specification. The classifier ignores shader transparency and uses uninflated BVH triangles. Near-contact samples remain explicitly classified, rather than counted as measured filled material.

All 29 native registration/preservation checks and all 6 filling checks pass on the saved model. These establish illustration geometry and matching PNG coordinates, not physical behavior. Physical simulation runs: zero.

## Lower two accepted assets retained

![Central SSG mechanical response](02_SSG_response_contrast_v30_preview_white.png)

![Pillar interaction view](03_pillar_context_v30_preview_white.png)

Both lower native scenes, raw PNGs, cropped assets and white previews are byte-identical to V29. No Pro inquiry, local Git write, full Figure 3 layout or source-document edit occurred. The manuscript retains its original SHA256, and the current reference-PPT snapshot remains unchanged. Only PNGs and Markdown are published; the editable four-scene Blender model and six-PNG asset archive are local deliveries.

[Previous version](../panel_a_v29/MODEL_REVIEW.md)
