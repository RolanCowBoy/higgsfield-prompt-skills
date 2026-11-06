---
name: hf-prompt-review
description: "Audit and repair prompts for Higgsfield image or video workflows, especially conflicting references, shot timing, object states, editing scope, and unreadable staging. Use when asked to review, debug, shorten, or improve an existing Higgsfield prompt; do not turn unrelated writing requests into a prompt audit."
---

# Higgsfield prompt review

Read [the shared contract](references/prompt-core.md). For a difficult conflict or revision family, consult [diagnostic patterns](references/diagnostic-patterns.md).

## Establish the evidence
Read the full prompt, supplied model/settings, available references, and any output or failure description. Identify the intended operation: new image, image edit, single shot, sequence, reference-motion generation, or existing-video edit. Do not critique an edit as if it were a text-only generation.

Separate three evidence levels:
- confirmed textual defect;
- likely risk that needs a generation to test;
- observed output defect, only when media was actually inspected.

Keep the user's primary event, approved identity, aesthetic, and explicit settings. Shortening is not permission to redesign the scene.

## Audit in order of consequence
1. **Inputs and authority:** Is every invoked attachment real and assigned a role? Are pose, appearance, lighting, and motion inherited from competing sources? Does the prompt rely on “same as before” or an unresolved export ID?
2. **Format and time:** Do duration, ratio, dimensions, and number of shots agree? Add explicit segment durations only when useful; sum them against the actual requested duration. Distinguish hard cuts from action beats.
3. **State and causality:** Make a small state table for hands, props, attachments, costume, seat positions, and damage if relevant. Flag a second handle that is detached before its break, a roof that reappears, or an overtaken vehicle returning ahead.
4. **Visibility:** Can the camera see the decisive action at that time and scale? An instruction about an offscreen expression cannot carry a visible story beat. A face reflected in a tiny dark mirror cannot carry unlimited micro-expressions.
5. **Geometry and movement:** Check eyelines, reflection paths, world versus screen directions, camera attachment, and relative velocities. State uncertainty when reference geometry cannot be inspected.
6. **Scope and style:** Check requested edits against locks. Distinguish deliberate mixed media from accidental stylistic contradictions. Restrict negative instructions to actual likely failures.
7. **Density and priority:** Identify competing events, repeated paragraphs, invisible details, and pseudo-precision. Preserve the indispensable action; reduce supporting detail first.

Do not classify natural bounce/fill as a second independent key, or normal pose-dependent occlusion as identity drift.

## Repair
For an unambiguous defect, produce a complete corrected prompt, not a patch requiring another conversation. Keep meaningful constraints and reference roles. Replace repetition with one authoritative statement and a short priority rule where needed.

If hard user requirements are mutually exclusive, explain why and give the nearest concrete alternatives. Do not choose an alternate duration or add a cut while describing the result as compliant. When a preference is merely inferred, state a reasonable assumption and proceed.

For a request to preserve original wording, edit narrowly and identify the changed passages. For a request to shorten, retain causal and state information before decorative adjectives.

## Return
Scale the answer to the issue:
- a few consequential findings with evidence labels;
- a copyable revised prompt, or two alternatives if a real choice is unavoidable;
- matching settings and reference mapping where relevant;
- the next test and its visible pass condition if the user is iterating.

Do not give a numeric quality score without a defined rubric and evidence. Do not claim the revision “will fix” a render you have not tested.
