---
name: hf-image-edit
description: "Write precise Higgsfield image-edit prompts for an existing base: local feature changes, character insertion, restyling, relighting, or changing object state while preserving unrequested properties. Use for targeted corrections and reference-guided edits; do not replace a small edit with a new scene."
---

# Higgsfield image editing

Read [the shared contract](references/prompt-core.md). Consult [edit patterns](references/edit-patterns.md) for multi-reference insertion, selective style transfer, and local revisions.

## Establish the edit boundary
Identify the actual base and the latest explicit changes. Keep source identity separate from scene style, camera, and lighting.
Build a small internal change/preserve map:
- change: exact features, region, pose, state, or visual properties;
- preserve: composition and approved identity/property anchors outside the change;
- allow as consequences: local occlusion, shadows, reflections, cloth folds, and silhouette changes caused by the authorized edit.

Resolve conflicts in favor of the user's newest explicit change within its scope. “Make the head larger” necessarily changes its silhouette; do not also lock every head pixel. Preserve other characters independently when only one is being altered.

## Select the edit operation
- **Local feature:** describe the direction and extent of change; use visually grounded relations rather than arbitrary percentages.
- **Character insertion/replacement:** distinguish base scene, identity donor, and any pose donor. Identify the figure to replace. Match scene rendering/light/contact while retaining the donor's defining shape.
- **Style or light transfer:** name transferred properties and excluded content. Keep composition/geography under the base's authority.
- **Damage/state change:** describe before and after; preserve identity and plausible remaining construction.
- **Repose/reframe:** acknowledge which geometry must change and which identity/materials stay.

If masking or a localized edit mode is actually available, use it where appropriate for preservation. Do not invent controls or claim pixel-exact protection from text alone.

## Write the smallest sufficient instruction
For one clear edit with one base, a short paragraph can suffice. For ambiguous multi-reference work, explicitly map the sources, then state edits and invariants.
Do not recite the entire scene unless it is needed to disambiguate preservation. Keep exclusions tied to likely unwanted changes.

Example structure:
Base → authorized changes → donor properties if any → integration requirements → retained properties.
Use actual attachment handles when known; otherwise keep descriptive labels outside the final runnable form and explain the needed binding.

When the user requests a past version's environment and a newer character, treat them as separate sources. Never use “make everything like image two” if image two should control only the character.

## Return and iterate
Return a copyable English edit prompt, optional reference map, and a brief statement of what changes. Respect prompt-only requests.
On an actual result, compare both success of the requested edit and collateral changes outside it. If identity drift is observed, narrow the edit and reassert a small set of defining anchors rather than piling on prohibitions.
Do not claim to have compared images that are unavailable. A text-only plan remains a plan until run and inspected.
