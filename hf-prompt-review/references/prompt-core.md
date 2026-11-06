# Shared Higgsfield prompting contract — v1

Apply these rules with the task-specific SKILL.md. This bundled copy makes the skill usable on its own; do not require other skills, this conversation, or the original project files.

## Establish the actual task
Distinguish prompt drafting, critique, and generation. Writing a prompt does not authorize starting a paid generation. If generation is explicitly requested, use the user's selected platform through available tools, preserve existing authorization, and report actual outcomes. Do not silently substitute another generator or claim a render was tested.

Use the user's language for discussion and English for the generation prompt unless requested otherwise. Keep settings, reference instructions, and explanatory notes outside the copyable prompt. For a simple edit, provide a short prompt without filling an unnecessary production questionnaire. For a complex shot, use named sections only where they resolve ambiguity.

## Ground references
Inspect supplied images/video when available. Distinguish what you observed from descriptions supplied by the user. If the media is unavailable, do not invent its visual details or claim to have seen it. Draft from known facts with descriptive reference labels; ask for the missing asset only if identity or geometry depends on it.

For each reference, record:
- role: identity, geometry, costume, pose, composition, motion, lighting, or surface style;
- properties to inherit;
- properties explicitly overridden or excluded;
- precedence if another reference governs the same property.

Use a compact table only when multiple references could be confused. For one obvious base image, one sentence is enough.
Use actual attachment identifiers exposed by the chosen interface. Descriptive labels such as BASE or CHARACTER are planning labels, not attachment handles. Resolve them before generation. Never transplant opaque UUIDs or fabricate upload references. Export notation such as <<<image_1>>> is not proof of syntax supported by another mode.

## Separate project identity from the general method
Retain approved facts: identity anchors, proportions, costume, handedness, prop state, style layers, lighting motivation, and previous-shot endpoint. Apply the newest explicit user changes to those facts. Do not import a yellow taxi, watercolor, golden-hour lighting, camera shake, a gender/age, or a comic emotional contrast from examples into unrelated work.

When continuity spans requests, use a compact project record: approved facts; current reference roles; scene starting/ending states; allowed changes; unresolved choices. Use available user-provided records or session context. Do not claim memory across sessions or create/update a file unless that is part of the task.

## Translate intent into visible evidence
Choose the indispensable viewer takeaway, then the visible action or image structure that communicates it. Describe large forms before micro-detail; visible features before invisible backstory. Match the description to shot scale. Separate subject movement, camera movement, and background motion.

For action, track cause → contact/reaction → follow-through → resulting state. Preserve object identity through state changes. For performance, use objective → obstacle → action toward a partner or object → visible change. Use a few expression cues where needed; do not ban expressive animation.

Choose a small set of critical requirements and rank them if tradeoffs matter. EXACTLY, NEVER, coordinates, frame counts, and percentages express intent; they are not enforcement mechanisms. Support indispensable precision with an appropriate source frame, layout, previz, or editing step when available.

## Check consistency before handing off
Check references, actual settings versus prose, start/end states, screen/world directions, visibility of the decisive action, permitted edits versus preservation, and whether the requested events can read in the duration.

Distinguish a beat within a shot from a camera cut. In N consecutive shots there are N−1 internal cuts unless an external opening/closing transition is separately requested. Do not silently change a user's hard duration, camera rule, or defining action to solve a conflict. Explain the smallest conflict and offer concrete alternatives; proceed with an explicit assumption only for nonessential choices.

Fix light in a declared coordinate system. A world-fixed sun need not remain camera-left after a reverse angle. One dominant motivated key may coexist with sky fill and bounce; do not demand impossible lighting geometry. Distinguish field of view, camera distance, lens projection, and sensor-dependent focal length; do not equate wide angle with fisheye.

For edits, preservation applies to unrequested properties. Allow the local occlusion, shading, and folds necessary for an authorized change. Do not promise pixel-exact preservation from a generative edit.

## Match settings to the selected mode
Do not hard-code a model's maximum duration, reference count, price, native resolution, or accepted syntax. Preserve supplied settings; verify current official Higgsfield/model documentation if making capability claims or preparing an actual run. When no model is selected, deliver a model-neutral draft and list only decisions that affect it.
Relevant official starting points:
- https://higgsfield.ai/creator-hub/help-center/getting-started/how-do-i-write-a-good-prompt
- https://higgsfield.ai/creator-hub/help-center/ai-models/how-do-i-use-seedance

Treat timestamps and technical numbers in natural-language prompts as approximate intentions unless the actual mode provides deterministic controls. Do not confuse setting a resolution in prose with selecting it in the UI/API.

## Deliver and iterate
Usually return: concise task interpretation; needed reference mapping/settings; one copyable prompt; a few visible acceptance checks. Omit redundant items. Honor "only the prompt."
Expand only for unresolved spatial or temporal complexity. Keep a private directing brief separate from the executable prompt rather than sending all analysis to the generator.

If given output media, inspect the whole relevant result. Separate observed faults from hypotheses. Change one suspected cause per iteration and preserve what already works. With prompt text only, report textual findings and proposed tests, not success rates.
