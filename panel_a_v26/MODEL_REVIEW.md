# Shallow native wave relief and vivid blue focus pillars

The SSG observation surface now carries actual shallow curved mesh relief. The two focus pillars use a more vivid blue, while the surrounding array stays pale blue.

![Native shallow waves and vivid blue pillars](03_pillar_context_v26_preview_white.png)

[Transparent PNG close-up asset](03_pillar_context_v26_asset.png)

Four smooth curved crests bow gently towards the pillar region. The largest illustrative relief is 0.12 mm, with tapered ends and zero displacement at silicone contact boundaries. A native Geometry Nodes modifier triangulates and subdivides the observation section, displaces actual vertices, and reconnects it to the retained bulk. There are no drawn wave lines, tubes, bitmap textures, arrows or shader Bump nodes. These crests are qualitative surface cues on the displayed section, not a calculated fluid trajectory or a newly exposed free liquid surface under the sealed cover.

The exact original V06 SSG shader graphs remain unchanged: diffuse/transparent mix opacity 0.22, roughness 0.40 and zero Principled transmission, with no volume shader or glass refraction. Investigation found that Boolean-generated cap vertices had received a zeroed point-color attribute even though the source mesh had the original uniform color. The native modifier restores the original uniform color on evaluated geometry as well. A narrow grazing softbox illuminates only the SSG to make the shallow relief visible. The two focus pillars use linear RGB (0.045, 0.26, 0.78); other material graphs are retained.

The frontal camera remains at zero yaw and roll with a slight 23-degree downward view. The full nominal 0.5 mm silicone/PDMS cover remains visible at 0.18 opacity. The filled enclosure, shared section through the pillars, directly exposed opaque pillar faces, and gentle 0.25 mm midpoint bow are retained. The bulk surface differs only within the 0.00003 mm boundary-weld tolerance and floating-point rounding.

31 checks pass after reopening. Actual relief vertices are present, evaluated surface colors match the original and are no longer black, material graphs match V06, camera rays reach both solid pillar caps before SSG, and all 30 section samples remain filled and non-overlapping. Camera, cover, background materials and source meshes/shape keys are preserved. These checks verify the illustration, not physical behavior. Physical simulation runs: zero.

## Other two assets retained

![Impact section](01_impact_section_v26_preview_white.png)

[Impact section PNG](01_impact_section_v26_asset.png)

![SSG response contrast](02_SSG_response_contrast_v26_preview_white.png)

[SSG response contrast PNG](02_SSG_response_contrast_v26_asset.png)

The other two raw renders are byte-identical to V25. Original DOCX/PPTX hashes are unchanged. No Pro inquiry, overall Figure 3 layout or local Git write occurred. Only browser-readable PNGs and Markdown are published. The editable native model and three-PNG archive are local deliveries. Temporary diagnostic and trial images are excluded from publication.

[Previous original-material restoration](../panel_a_v25/MODEL_REVIEW.md)
