# XXD Panel 045 | Gentle Rounded Isometric Block Sculpture Production Prompt

## Runtime complete-canvas contract — highest priority

- `TOP_BOTTOM` and `LEFT_RIGHT` default to one complete finished generation using the current source as a high-fidelity edit/reference input. Do not pre-split the job into photographic and design halves.
- Top-bottom keeps the faithful source in approximately the upper 50% and performs this style transformation below; left-right uses the faithful source in approximately the left 50% and the transformation on the right. Unify both regions through colour, light, rhythm, typography, and meaning.
- `DESIGN_ONLY` and `WALLPAPER_PACK` use the complete canvas while the source remains an invisible identity/content reference. Recompose every wallpaper separately for its device.
- `FINAL CANVAS` means the ratio/pixels of the whole finished artwork and must be explicitly resolved before generation; never apply source dimensions silently. `DESIGN FRAME` is used only if a failed complete-canvas retry triggers deterministic composition fallback.
- Retry a failed complete canvas once against the failed constraint only. Scripted composition is allowed only after that retry still fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless pixel calibration.

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is available through the current built-in image tool or a configured compatible route, use it first for the high-fidelity reference/edit and complete-canvas generation required by this prompt.
- Also support Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model only when the actual route can preserve the source, realise the whole finished canvas, render the target-language text, and accept the multiple references needed by a linked wallpaper pack.
- An alternative model changes only the generation route. It must not change this prompt's modes, canvas, source visibility, copy, locale, wallpaper relationship, or complete-canvas-first / composition-fallback-only logic. Do not silently downgrade a hard requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task, but never echo, display, log, or expose their value in chat, prompts, or diagnostics. Do not persist them or modify global route configuration unless explicitly requested.
- Judge availability by actual image capability, not by a provider name or one missing environment variable.

Process only the source photograph explicitly supplied for this fresh task. Privately lock identity, structure, pose, direction, action, function, opening, relation, emotional implication, and source colour. Preserve at least three source-specific cues and never borrow from another input, old output, or sample.

## Aesthetic transformation

Deconstruct, select, distil, and rebuild the source as a gentle isometric block sculpture whose rounded tactile modules preserve its distinctive volume, axis, curves, interlocks, overlaps, occlusions, and negative spaces without literal LEGO copying or pixelisation.

Use this causal sequence: analyse volume, axis, curves, overlap, and negative space → preserve three defining cues → simplify into rounded modular masses → compose through stacking, nesting, crossing, suspension, and source-earned misalignment → translate source colour into lighter cleaner healing hierarchy → render tactile matte pulp, wood, wax, or soft material → integrate microtype with seams and axes.

## Hard visual requirements

- Preserve at least three cues across overall volume, proportion, axis, curve, pose, direction, overlap, occlusion, opening, negative space, or relation.
- Use rounded, simple, tactile modular masses with real isometric depth. Stack, join, nest, cross, float, or gently misalign them according to source structure, not mechanical exploded parts.
- Analyse the source's lively principal colours, temperature, value hierarchy, warm-cool response, and key accent; translate them into lighter, cleaner, airy healing colour without importing absent hues or a fixed palette.
- Build rhythm through principal colour area, supporting layers, related value steps, and one tiny lively accent: gentle but energetic, playful but not sugary.
- Use matte diffuse tactile material suggesting paper pulp, wood, soft wax, chalk, or flexible composite, with rounded edges and light shadows; reject glossy plastic, metal, heavy CG, and cheap toys.
- Use scale, height, depth, local suspension, density shifts, and whitespace to create one sculptural focus rather than a full toy scene.

## Copy and locale

Obey the resolved automatic, exact-user, or text-free copy mode and target locale. Use one two-to-five-word source-bound title plus only useful state, place, supplied number, direction word, or micro-note; do not use years. Align native microtype with module edges, seams, axes, negative space, overlaps, or occlusion so it becomes part of the sculpture's rhythm. Preserve exact user wording verbatim. In text-free mode render no letters, numbers, captions, labels, or pseudo-text.

## Mode and acceptance


Reject: fixed healing palette, imported colours, literal LEGO copy, pixelisation, mechanical parts, blocky anatomy, glossy plastic, metal, heavy CG, candy colour, children's cartoon, cheap toy, e-commerce display, full game scene, template sculpture. Also reject logos, watermarks, swatches, UI, device mockups, unsupported facts, fake foreign text, and unreadable copy.

If any hard condition fails, correct the generated bitmap. Never fake the artwork with programmatic drawing, SVG, HTML, Canvas, 3D code, or a post-composited type overlay.
