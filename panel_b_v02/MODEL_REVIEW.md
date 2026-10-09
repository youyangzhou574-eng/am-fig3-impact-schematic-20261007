# Simplified impact experiment with Figure 3a visual style

The human requested a style consistent with panel a, a simpler frame and removal of the host computer. The apparatus is now a compact scientific schematic: a blue cylindrical head with a dark rear force sensor, a layered circular specimen on a gray support, and two pale guide posts with a simple transverse guide beam. Computer, external lead, connectors, screws, extrusion grooves, tapered brackets and supporting-plate holes are removed.

![Simplified impact experiment](01_simple_impact_experiment_v02_preview_white.png)

[Transparent PNG](01_simple_impact_experiment_v02_asset.png) · [Full 2000 x 1700 RGBA canvas](01_simple_impact_experiment_v02_full_canvas.png)

## Style correspondence

Actual shader graphs are imported from the accepted `panel_a_v37` native model: white silicone, pale cyan SSG, complete PDMS cover, gray rigid support and the saturated blue used by the foreground pillars. The guide frame uses a copy of panel a's pale section shader. These are visual-style assignments, not claims about the actual guide-frame material.

The Standard/None color transform, white studio world, softbox arrangement and frontal 18-degree overhead view match panel a. The SSG's generated Boolean surfaces carry the same peripheral pale cyan palette, so the style transfer does not introduce black cavity faces. All visible hardware uses matte nonmetallic shaders rather than polished photo-like steel.

## Experiment representation

The head is depicted near the sample to make the impact relationship clear in a compact illustration. The drawn 14 mm clearance is a composition parameter, not an experimental release height. The manuscript's 370 g mass and 10/20/30 cm release heights remain documented inputs. No release-height scale or motion arrow is drawn.

The rear force sensor remains above the impactor, as specified in the original manuscript. The lower block is the rigid support. The existing circuit-free 74 mm specimen mesh and its 1 mm base, 4.5 mm intermediate region and 0.5 mm cover are retained without a geometry/topology change; only a rigid vertical translation and shader assignment change. The source-a model and previous detailed b model remain byte-preserved.

## Verification

All 28 fresh native checks pass after reopening the saved model. These checks include exact source-a shader graphs and world/view correspondence, removal of the computer and mechanical detail, preserved specimen mesh and layer dimensions, coaxial head position, rear sensor placement, support contact and a clearly identified schematic approach pose. Specimen volumes remain closed, and evaluated SSG plus pillars fill the intermediate enclosure.

Native Blender illustration only. No physical solver, new Pro message, source-document edit or local Git write. Only PNGs and Markdown are published; the editable native model and receipts remain local. No overall Figure 3 composition, rendered text, arrows or experimental force plot is added.

[Matching panel a](../panel_a_v37/MODEL_REVIEW.md) · [Previous apparatus and original-source audit](../panel_b_v01/MODEL_REVIEW.md)
