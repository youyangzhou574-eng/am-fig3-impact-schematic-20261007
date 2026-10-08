# Original reference SSG material restored directly

The human rejects the later glass-like transparency and explicitly requests the earliest SSG material. The supplied reference image is the V06 native Blender full-panel render.

![Original SSG material with frontal blue pillars](03_pillar_context_v25_preview_white.png)

[PNG close-up asset](03_pillar_context_v25_asset.png)

The original V06 **SSG transparent interior** and **SSG contact interface - no coincident surface** material datablocks are loaded from the saved native file. Their complete shader graphs are copied into the current local SSG material slots. The original uniform point-color attribute is restored as well. Fresh graph signatures match the original material definitions exactly.

This original material uses a 0.22 diffuse/transparent surface mix, roughness 0.40 and zero Principled transmission. It has no volume scattering, glass refraction or wave-normal shader. The contact interface is fully transparent to avoid a duplicated surface layer at silicone contact. The later refractive/volume/wave material experiments are removed. These settings are illustrative, not measured physical material properties.

The current blue foreground pillars and pale-blue background array are retained. Camera yaw and roll remain zero, with the existing slight 23-degree downward view. The full nominal 0.5 mm silicone/PDMS top cover remains displayed at 0.18 opacity. Geometry, the filled enclosure, the common y=1.70 mm section exposing bare pillar faces, the gentle 0.25 mm midpoint bow and studio lights are retained. The view has no rendered text, arrows or leaders.

25 native checks pass after reopening. They establish exact original shader definitions and color attribute, no refractive/volume/bump nodes, unchanged original V06 source-file hash, preserved geometry/camera/non-SSG materials/lights, complete translucent cover, camera rays reaching solid pillar caps before SSG, and 30 filled non-overlapping section samples. This is an illustration, not a physical solver result.

## Other two assets retained

![Impact section](01_impact_section_v25_preview_white.png)

[Impact section PNG](01_impact_section_v25_asset.png)

![SSG response contrast](02_SSG_response_contrast_v25_preview_white.png)

[SSG response contrast PNG](02_SSG_response_contrast_v25_asset.png)

These two raw renders are unchanged. Original DOCX/PPTX hashes are unchanged. No Pro inquiry, physical simulation, overall Figure 3 layout or local Git write occurred. Only browser-readable PNGs and Markdown are published; the editable native model and PNG archive are local deliveries. Unaccepted refractive trial images are excluded.

[Original V06 material reference](../panel_a_v06/MODEL_REVIEW.md)
