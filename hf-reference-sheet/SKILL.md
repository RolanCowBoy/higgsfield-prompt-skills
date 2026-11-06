---
name: hf-reference-sheet
description: "Write Higgsfield prompts for turnaround views, expression sheets, pose sheets, or vehicle/object view sheets that preserve an approved design. Use for character sheets, model sheets, лист персонажа, ракурсы, эмоции and позы; distinguish consistent views of one subject from a grid of new character concepts."
---

# Higgsfield reference sheets

Read [the shared contract](references/prompt-core.md). Consult [sheet patterns](references/sheet-patterns.md) for turnarounds, expressions, and mixed layouts.

## Identify the source and the sheet purpose
Use the approved reference as the identity authority. If it is unavailable, distinguish a textual provisional sheet from a sheet verified against the actual design. Do not invent unseen back details as if confirmed; preserve what is known and identify any necessary design inference.

Separate:
- turnaround: different viewing angles, normally a stable pose;
- expression sheet: face/neck performance with identity held;
- pose sheet: body action with identity and costume held;
- mixed presentation sheet: several purposes, with deliberate panel groups;
- object/vehicle sheet: same construction and markings across views.

Honor a requested combined sheet when feasible. If it would make faces or full figures too small, propose a practical split or a clearer mixed layout without silently dropping requested views. Ask only when a consequential choice cannot be inferred.

## Design the layout
Specify a count, panel order, view or expression per panel, and framing. Use panel descriptions that correspond to actual positions, not a vague “different angles.”
For turnarounds, align the ground line and keep scale and neutral pose comparable; preserve anatomical left/right rather than mirroring asymmetrical marks.
For face expressions, use consistent portrait crop and head scale. Change brows, eyelids, cheeks, mouth, and head attitude as required without changing skull design or baseline eye placement.
For poses, show the complete silhouette and contact points, allow margins, and keep costume/accessories attached plausibly.
For objects, preserve wheel count, structural landmarks, livery and orientation; do not mistake perspective occlusion for removal.

Do not demand identical proportions in pixels across a foreshortened pose. Preserve anatomical design, allowing projection and expression deformation appropriate to the style.

## Write the prompt
Lead with the sheet type and the approved identity source, then layout, panel-specific changes, shared invariants, background/light, and relevant restrictions. Make clear that every panel is the same subject.
Use uniform lighting when comparability is the purpose. Preserve a user-requested stylized or narrative presentation when it does not hide needed information.
Labels are optional. Do not require generated small text unless the user wants it; if exact typography matters, suggest adding it separately.

Do not implicitly change a single-image output into a batch. For multiple outputs, provide a common identity block and a separate prompt for each requested sheet or view.

## Return and inspect
Provide the prompt, the panel map, and a few acceptance checks, unless the user requests prompt-only.
On actual outputs, compare facial landmarks, hair silhouette, costume construction, asymmetrical details, body proportions, scale, and missing/cropped panels.
If a specific view drifts, revise that view with the approved source rather than redesigning all views. Do not promise an animation-production model sheet from a single unverified render.
